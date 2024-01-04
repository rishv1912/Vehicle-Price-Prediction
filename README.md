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

Dependent Variable (Target)
- `Selling_Price:`This is our dependent variable or target variable.


- `Car_Name:` Name of the car
- `Year:` Year of Manufacture
- `Present_Price:` Current price for selling
- `Kms_Driven:` Total Kilometres has been driven
- `Fuel_Type:` Type of fuel
- `Seller_Type:` Individual or Dealer
- `Transmission:` Manual or Automatic
- `Owner:` Is there any owner or not


Selling_Price: This is likely your dependent variable or target variable as it represents the price you want to predict.
Independent Variables (Features):

Year: The age of the car could have a significant impact on its selling price. Newer cars may have higher prices.
Present_Price: The current market price of the car could strongly influence its selling price.
Kms_Driven: The distance the car has been driven may affect its condition and, consequently, its selling price.
Fuel_Type: The type of fuel the car uses may influence its demand and, consequently, its price.
Seller_Type: Whether the seller is a dealer or an individual may impact the selling price.
Transmission: The type of transmission (manual/automatic) could affect the selling price.
Owner: The number of previous owners might influence the perceived value of the car.
Potentially Important Variables:

Car_Name: While the specific name may not directly impact the price, it could indirectly reflect the brand, model, or other features that affect the value.

We have to predict the price of the vehicles. 
So the target variable or label is "selling_price", all the others variables are features.