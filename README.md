__Data__
This data is from the UCI Machine Learning Repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios, including the destination, current time, weather, and passenger, and then asks people whether they will accept the coupon if they are the driver. There are three possible answers people can choose from:

“Right away”
“Later, before the coupon expires”
“No, I do not want the coupon”
The first two responses are labeled as “Y = 1,” and the third is labeled as “Y = 0.” There are five different types of coupons: Less expensive restaurants (under $20), coffee houses, carryout and takeaway, bars, and more expensive restaurants ($20–$50).

__File Name__ coupons.csv

__Goal__

Identify the characterstics and make recommendations about people who accepted either a bar or coffee house coupon.

__Who will accept the bar coupon?__

 ![Types of Coupon]( https://github.com/msking2/Practical_Assessment/blob/main/Types%20of%20Coupons%20vs%20Coupons%20Accepted.png)
 ![Types of Coupon](https://github.com/msking2/Practical_Assessment/blob/main/Histogram%20of%20Temperatures.png )

•	Based on the analysis, around 750 people accepted the bar coupon.

•	Per the prompt, there were 3 distinct temperatures.

•	Based on the requested scenarios, here is the results:

    o	25.3% Acceptance rate for people who went to the bar 3 or fewer times a month
    o	7.6% Acceptance rate for people who went to the bar more than 3 times a month
    o	14.5% Acceptance rate for people who went to the bar > 1 time a month and are older than 25
    o	6.9% Acceptance rate for people who went to the bar > 1 time a month and had passengers that were not a kid and had occupations other than farming, fishing, or forestry.
    o	6.9% Acceptance rate for people who go to bars more than once a month, had passengers that were not a kid, and were not widowed
    o	5.9% Acceptance rate for people who go to bars more than once a month and are under the age of 30
    o	2.8% Acceptance rate for people who go to cheap restaurants more than 4 times a month and income is less than 50K
•	Based, on these observations, drivers who go to the bar between 1 - 3 times a month, older than 25, with income > $50 K were more likely to accept the coupon for the bar.

__Recommendation:__ People who meet this criteria should be targeted to receive this coupon.

__Independent Investigation__

Explore the acceptance rate of the coffee house coupon.

•	The coffee house coupon was accepted ~50% of the time.
 
•	People with bachelors or some college – no degree were more likely to accept the coupon.
 ![Types of Coupon]( https://github.com/msking2/Practical_Assessment/blob/main/Education%20of%20People%20who%20Accepted%20a%20Coupon.png)
 
•	People making between $12,500 and $62,499 were more likely to accept the coupon.
 ![Types of Coupon](https://github.com/msking2/Practical_Assessment/blob/main/Income%20of%20People%20who%20Accepted%20a%20Coupon.png )
 
•	People who were alone or with friends were more likely to accept the coupon.
 ![Types of Coupon](https://github.com/msking2/Practical_Assessment/blob/main/Passanger%20of%20People%20who%20Accepted%20a%20Coupon.png )
 
•	Males/females accepted the coupon at roughly the same rate.
 ![Types of Coupon](https://github.com/msking2/Practical_Assessment/blob/main/Gender%20of%20People%20who%20Accepted%20a%20Coupon.png )
 
•	People between 21 and 26 were more likely to accept the coupon.
 ![Types of Coupon](https://github.com/msking2/Practical_Assessment/blob/main/Age%20of%20People%20who%20Accepted%20a%20Coupon.png )
 
•	People who were single or married were more likely to accept the coupon.
 ![Types of Coupon](https://github.com/msking2/Practical_Assessment/blob/main/Marital%20Status%20of%20People%20who%20Accepted%20a%20Coupon.png )

•	People who went to the coffee house more than 0, but less than 3 times were more likely to accept the coupon.
 ![Types of Coupon](https://github.com/msking2/Practical_Assessment/blob/main/Number%20of%20Times%20Visiting%20a%20Coffee%20House%20of%20People%20who%20Accepted%20a%20Coupon.png)

•	People who went to the coffee house more than 0, but less than 3 times, who were single or married, between 21 and 26, who were alone or with friends and made between $12,500 and $62,499. They accepted the coupon at a rate of 10.6%.

__Recommendation:__ Engage with people in their 20’s who got to a coffee house less than 3 times a month and make less than $63 K to give coupons to.
