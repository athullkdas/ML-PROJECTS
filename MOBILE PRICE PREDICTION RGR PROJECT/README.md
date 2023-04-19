
# MOBILE PRICE PREDICTION

### ABOUT DATASET :
Mobile price depends on various factors such as brand model,base color,processor,screen size,ROM,RAM,display size,num rear camera,num front camera,battery capacity,ratings,num of ratings,sales price,discount percent,sales. In this dataset, we want to estimate the price of mobile phones using the above features.

## DETAILS ABOUT THE DATASET :
brand: The name of the brand of the device.
model: The specific model of the device.
base_color: The primary color of the device.
processor The CPU type of the device.
screen_size: The diagonal size of the device's screen, usually measured in inches.
ROM: The amount of built-in storage in the device, measured in gigabytes (GB).
RAM: The amount of memory in the device, measured in gigabytes (GB).
display_size: The physical size of the device's display, usually measured in inches.
num_rear_camera: The number of cameras on the back of the device.
num_front_camera: The number of cameras on the front of the device.
battery_capacity: The capacity of the device's battery, measured in milliampere-hours (mAh).
ratings: The average rating of the device on a scale of 1 to 5 stars.
num_of_ratings: The total number of ratings given to the device.
sales_price: The current price of the device.
discount_percent: The percentage discount being offered on the device.
sales: The total number of sales of the device.

## DATASET COLUMNS

Data columns (total 16 columns):

    Column            Non-Null Count  Dtype  
---  ------            --------------  -----  
 0   brand             430 non-null    object 

 1   model             430 non-null    object 

 2   base_color        430 non-null    object 

 3   processor         430 non-null    object 

 4   screen_size       430 non-null    object 

 5   ROM               430 non-null    int64  

 6   RAM               430 non-null    int64  

 7   display_size      430 non-null    float64

 8   num_rear_camera   430 non-null    int64  

 9   num_front_camera  430 non-null    int64 

 10  battery_capacity  430 non-null    int64 

 11  ratings           430 non-null    float64

 12  num_of_ratings    430 non-null    int64 

 13  sales_price       430 non-null    int64 

 14  discount_percent  430 non-null    float64

 15  sales             430 non-null    float64
 
dtypes: float64(4), int64(7), object(5)
# CONCLUSION
The data points in the scatter plot are tightly clustered around the regression line, indicating a strong correlation between the variables. This suggests that changes in ROM,processor,RAM,model have a significant impact on SALES PRICE
