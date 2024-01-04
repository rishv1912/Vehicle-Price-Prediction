# Vehicle Price Prediction
> Get the data : [Link](https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho)


### Cloning the repository
--> Clone the repostiory using the command below:
``` 
https://github.com/rishv1912/Vehicle-Prediction.git
```

--> Move into the directory where we have the project file:

```
cd  Vehicle-Prediction
```

--> Create a virtual environment:
>You can use pip3 or pip according to your path variable

For Mac
```
# Let's install the virtual environment
pip3 install virtualenv

# Then we create our virtual environment
python3 -m venv env-vehicle
```

For Windows
```
# Let's install the virtual environment
pip install virtualenv

# Then we create our virtual environment
virtual env-vehicle
```

--> Activate the virtual environment:

For Mac
```
source env-vehicle/bin/activate
```

For Windows
```
env-vehicle\scripts\activate
```

--> Install the requirements:

>Again use pip or pip3 according your path variable, if pip doesn't work use pip3.

```
pip3 install -r requirements.txt
```


# About Dataset

We don't have much description about the data


**Data Dictionary:-** 

- `Car_Name:` Name of the car
- `Year:` Year of Manufacture
- `Selling_Price:` Price for selling
- `Present_Price:` Current price for selling
- `Kms_Driven:` Total Kilometres has been driven
- `Fuel_Type:` Type of fuel
- `Seller_Type:` Individual or Dealer
- `Transmission:` Manual or Automatic
- `Owner:` Is there any owner or not


We have to predict the price of the vehicles. 
So the target variable or label is "selling_price", all the others variables are features.