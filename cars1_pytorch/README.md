# city_cars
In the neroset_model will be using lr.pth and lr_1pth.
Base:
System - Ubuntu20.04.06lts
System - Ubuntu22.04.05lts
System - Ubuntu24.04.01lts
Programming environment - Python3.8.10.2.11
Programming environment - Python3.9.5.3
Programming environment - Python3.10.12.2
Programming environment - Python3.11.0-rc2
Programming environment -Python3.12.2
Install:
Command for install Python:
sudo apt install python3.8
sudo apt install python3.9
sudo apt install python3.10
sudo apt install python3.11
sudo apt install python3.12
Check version Python:
Python3 --version
Command for install pip:
sudo apt install python3-pip
Check version Python:
Python3 --version
Check version pip:
pip3 --version
Others.
Install:
pip3 install numpy
pip3 install pandas
pip3 install sklearn # dipricated
# https://github.com/scikit-learn/scikit-learn/issues/8215
pip3 install scikit-learn
pip3 install tqdm
pip3 install torch
Check install python-libs:
command python3.8
command python3.9
command python3.10
command python3.11
command python3.12
import numpy
import numpy as np
import pandas
import pandas as pd
import sklearn
import tqdm
import torch
Base:
https://www.kaggle.com/datasets/ananaymital/us-used-cars-dataset
License:
Data files © Original Authors
Database:
car.csv
20 values('listing_id', 'listed_date', 'back_legroom', 'year', 'front_legroom', 'body_type', 'engine_displacement', 'engine_type', 'fuel_tank_volume', 'fuel_type', 'width', 'length', 'height', 'model_name', 'horsepower', 'major_options', 'price', 'city_fuel_economy', 'city', 'make_name')
300000 strings
target = city, make_name
Models:
lr.pth
lr_1.pth
File:
body_type.csv
city.csv
engine_type.csv
fuel_type.csv
major_options.csv
make_name.csv
model_name.csv