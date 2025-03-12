# cifar-10

My goal with this project is to develop a loose personal framework for subsequent ML/AI projects and endeavors.
The CIFAR-10 dataset will be used to:

- ~~perform exploratory data analysis~~
- create data processing pipelines
- ~~train and test classical ML models~~
- train and test personally architected neural networks
- train and test pretrained or pre-architected neural networks

### Technology Used

python 3.10, pandas, scikit-learn, pytorch, jupyter lab

### Setup

```
# create virtual environment
virtualenv -p=/usr/bin/python3.10 ./venv

# install packages
pip install -r requirements.txt
```

### Running Jupyter lab on a remote server

```
jupyter lab --no-browser --ip=100.109.213.114 --port=8080

# run in background
jupyter lab --no-browser --ip=100.109.213.114 --port=8080 > logs/jupyter.log 2>&1 &
```

