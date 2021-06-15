
Anaconda Install
----------------

1. Install PyMC3 using conda
2. This should install theano as well, install gpuarray if that was not installed using 
   conda install pygpu

3. Test theano with the given file by setting the theano flag to use OpenCL as a compute backend. The value for that is 
   
   opencl:platformid:deviceid
   where deviceid is 
   1. Intel CPU
   2. Intel GPU
   3. AMD Radeon 5300 GPU

   THEANO_FLAGS=device=opencl0:0 python test_theano.py
   
Note: This can cause issues such as multiprocessing issues on all versions of PyMC3 except for the latest version on MacOS. The latest version runs into a pickling issue for models, hence runs on a single thread.   
   

Docker install (Not stable!)
--------------

1. docker pull pymc/pymc3
2. docker run -it pymc/pymc3 bash
3. python setup.py build
4. python setup.py install
5. pip install scikit-learn graphviz
6. conda install -c conda-forge python-graphviz


Verify PyMC3 install
--------------------

```
import pymc3 as pm
import sklearn
import numpy as np
import pandas as pd
from sklearn import datasets
import theano as tt
import os

tt.config.gcc.cxxflags = "-Wno-c++11-narrowing"
df = datasets.load_iris()
iris_data = pd.DataFrame(df['data'], columns=df['feature_names'])
iris_data['target'] = df['target']

y_s = iris_data.target
x_n = iris_data.columns[:-1]
x_s = iris_data[x_n]
x_s = (x_s - x_s.mean()) / x_s.std()
x_s = x_s.values

with pm.Model() as model_mclass:
    alpha = pm.Normal('alpha', mu=0, sd=5, shape=3)
    beta = pm.Normal('beta', mu=0, sd=5, shape=(4,3))
    μ = pm.Deterministic('μ', alpha + pm.math.dot(x_s, beta))
    θ = tt.tensor.nnet.softmax(μ)
    yl = pm.Categorical('yl', p=θ, observed=y_s)
    trace_s = pm.sample(2000, chains=4, cores=4)

```

Git Local Hooks
---------------

Push this in the pre-commit file in the global hooks folder

if [ -e ./.git/hooks/commit-msg ]; then
    ./.git/hooks/commit-msg "$@"
fi

This gets deleted when the Githooks folder is replaced, so run this explicitly

./.git/hooks/post-commit


