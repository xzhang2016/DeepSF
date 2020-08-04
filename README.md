# DeepSF
DeepSF is a deep learning framework for essential gene prediction based on sequence and multiple functional data.

# Requirements
The code is based on python 3. It depends on several python packages, such as numpy, keras, scikit-learn, networkx, pandas, tensorflow, node2vec, gensim.

# Usage
For network features, please follow the instructions of [node2vec](https://github.com/aditya-grover/node2vec)(or [here](https://github.com/eliorc/node2vec)
). 

Command line usage:
```
$python main.py  --expName <experiment name>  --embedF <embedF> --kfold <cv fold>
```
