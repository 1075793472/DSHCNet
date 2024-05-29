# DSHCNet
## Install
To use EMPHCN you must make sure that your python version is greater than 3.7. If you don’t know the version of python you can check it by:
```python
python
>>> import platform
>>> platform.python_version()
'3.7.13'
```
## Environment Requirement
The required packages are as follows:
- scikit-learn==0.21.3
- cobra==0.22.1
- joblib==1.1.0
- numpy==1.21.6
- optlang==1.5.2
- pandas==1.3.5
- torch==1.9.0
- torch_geometric==1.7.2
- torch_scatter==2.0.8
- torch_sparse==0.6.11
- tqdm==4.65.0
```bash
python main.py --dataset T1
```
### Quick start
We use the dataset BiGG to illustrate an example. 

```bash
python main.py
```

