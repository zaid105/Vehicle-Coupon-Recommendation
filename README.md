# Vehicle-Coupon-Recommendation<br><br>
# About Dataset
Source:

Tong Wang, tong-wang '@' uiowa.edu, University of Iowa<br>
Cynthia Rudin, cynthia '@' cs.duke.edu, Duke University<br>
<br><br>
Data Set Information:
<br><br>
This data was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios including the destination, current time, weather, passenger, etc., and then ask the person whether he will accept the coupon if he is the driver. <br>
Wang, Tong, Cynthia Rudin, Finale Doshi-Velez, Yimin Liu, Erica Klampfl, and Perry MacNeille. 'A bayesian framework for learning rule sets for interpretable classification.' The Journal of Machine Learning Research 18, no. 1 (2017): 2357-2393.
<br><br>
# Attribute Information:
<br><br>
destination: No Urgent Place, Home, Work<br>
passanger: Alone, Friend(s), Kid(s), Partner (who are the passengers in the car)<br>
weather: Sunny, Rainy, Snowy<br>
temperature:55, 80, 30<br>
time: 2PM, 10AM, 6PM, 7AM, 10PM<br>
coupon: Restaurant(<$20), Coffee House, Carry out & Take away, Bar, Restaurant($20-$50)<br>
expiration: 1d, 2h (the coupon expires in 1 day or in 2 hours)<br>
gender: Female, Male<br>
age: 21, 46, 26, 31, 41, 50plus, 36, below21<br>
maritalStatus: Unmarried partner, Single, Married partner, Divorced, Widowed<br>
has_Children:1, 0<br>
education: Some college - no degree, Bachelors degree, Associates degree, High School Graduate, Graduate degree (Masters or Doctorate), Some High School<br>
occupation: Unemployed, Architecture & Engineering, Student,<br>
Education&Training&Library, Healthcare Support,<br>
Healthcare Practitioners & Technical, Sales & Related, Management,<br>
Arts Design Entertainment Sports & Media, Computer & Mathematical,<br>
Life Physical Social Science, Personal Care & Service,<br>
Community & Social Services, Office & Administrative Support,<br>
Construction & Extraction, Legal, Retired,<br>
Installation Maintenance & Repair, Transportation & Material Moving,<br>
Business & Financial, Protective Service,<br>
Food Preparation & Serving Related, Production Occupations,<br>
Building & Grounds Cleaning & Maintenance, Farming Fishing & Forestry<br>
income: $37500 - $49999, $62500 - $74999, $12500 - $24999, $75000 - $87499,<br>
$50000 - $62499, $25000 - $37499, $100000 or More, $87500 - $99999, Less than $12500<br>
Bar: never, less1, 1~3, gt8, nan4~8 (feature meaning: how many times do you go to a bar every month?)<br>
CoffeeHouse: never, less1, 4~8, 1~3, gt8, nan (feature meaning: how many times do you go to a coffeehouse every month?)<br>
CarryAway:n4~8, 1~3, gt8, less1, never (feature meaning: how many times do you get take-away food every month?)<br>
RestaurantLessThan20: 4~8, 1~3, less1, gt8, never (feature meaning: how many times do you go to a restaurant with an average expense per person of less than $20 every month?)<br>
Restaurant20To50: 1~3, less1, never, gt8, 4~8, nan (feature meaning: how many times do you go to a restaurant with average expense per person of $20 - $50 every month?)<br><br>
toCoupon_GEQ15min:0,1 (feature meaning: driving distance to the restaurant/bar for using the coupon is greater than 15 minutes)<br>
toCoupon_GEQ25min:0, 1 (feature meaning: driving distance to the restaurant/bar for using the coupon is greater than 25 minutes)<br>
direction_same:0, 1 (feature meaning: whether the restaurant/bar is in the same direction as your current destination)<br>
direction_opp:1, 0 (feature meaning: whether the restaurant/bar is in the same direction as your current destination)<br>
Y:1, 0 (whether the coupon is accepted)<br><br>
## Key Features

- **Exploratory Data Analysis (EDA):** Detailed exploration of the dataset to understand distributions, correlations, and patterns.
- **Feature Engineering:** Creation of new features or transformations to enhance model performance.
- **Data Visualization:** Visual representations of key insights and trends using charts and graphs.
- **Hypothesis**: Test Null Hypothesis

