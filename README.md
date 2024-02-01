# CDLD

## Dependencies

Require

- Python == 3.8
- PyTorch == 1.11
- PyTorch-Geometric == 2.0.3

Install other packages using following command at root directory of the repository

```
pip install -e .
```

## Dataset 

Download dataset at ./data from following links

```
https://drive.google.com/file/d/19SOqzYEKvkna6DKd74gcJ50Wd4phOHr3/view?usp=share_link
```
## Usage

To run on one dataset, please execute following commands in the directory ./scripts

```
python causal.py --dataset collab --log_dir ../logs/collab --device_id X 
python causal.py --dataset yelp --log_dir ../logs/yelp --device_id X 
```

To reproduce the main results, please execute following commands in the directory ./scripts. Change the 'resources' in the script.py as available GPU ids.

```
python script.py -t run
python script.py -t show
```



