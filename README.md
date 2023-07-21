# Mobile-Phone-Price-Prediction-Classification-Project

## Problem Statement

In the competitive mobile phone market companies want to understand sales data of mobile phones and factors which drive the prices. The objective is to find out some relation between features of a mobile phone(eg:- RAM, Internal Memory, etc) and its selling price. In this problem, we do not have to predict the actual price but a price range indicating how high the price is.

### Data Description -

Battery_power - Total energy a battery can store in one time measured in mAh

Blue - Has bluetooth or not

Clock_speed - speed at which microprocessor executes instructions

Dual_sim - Has dual sim support or not

Fc - Front Camera mega pixels

Four_g - Has 4G or not

Int_memory - Internal Memory in Gigabytes

M_dep - Mobile Depth in cm

Mobile_wt - Weight of mobile phone

N_cores - Number of cores of processor

Pc - Primary Camera mega pixels

Px_height - Pixel Resolution Height

Px_width - Pixel Resolution Width

Ram - Random Access Memory 

Touch_screen - Has touch screen or not

Wifi - Has wifi or not

Sc_h - Screen Height of mobile in cm

Sc_w - Screen Width of mobile in cm

Talk_time - longest time that a single battery charge will last when you are

Three_g - Has 3G or not -Wifi - Has wifi or not

Price_range - This is the target variable with value of 0(low cost), 1(medium cost), 2(high cost) and 3(very high cost).


### DATASET INFORMATION
I have made project on mobile phone price prediction the basis of pre-stored data, if a person wants to invest or starts his/her business in phone market this project will mainly helps in selecting the range of mobile price. Here is the link to dataset which was used

link:- https://drive.google.com/file/d/1i8bO3xv3x8SzXSeSkDl-2qYjCyc9vxA2/view

### Graphs

In this project we have to predict the price range of mobile phone and for that I have created visual representation of given data that how different features affect the price range of phone. As shown in graph below there is relation between price range and RAM, a conclusion can be made that RAM is directly proportional to price range.  

![image](https://github.com/jaydeepjadav/Mobile-Phone-Price-Prediction-Classification-Project/assets/120647862/6fe96490-1951-4b74-bb3f-8c4a44c4b9f4)

From the below figure we can easily understand that with increasing the screen width price range decreases. Reason could be as screen width increase it gets incomfortable to handle mobile phones so its better to keep optimal width.

![image](https://github.com/jaydeepjadav/Mobile-Phone-Price-Prediction-Classification-Project/assets/120647862/31b647e3-26a5-4c90-bf29-b9ab9f89691d)

Let's check for another feature with respect to price range and no. of cores that is whether a phone is 3g or not. And from the look it's easily comparable that phones having 3g network system have higher price than without 3g feature and that too with same no. of cores

![image](https://github.com/jaydeepjadav/Mobile-Phone-Price-Prediction-Classification-Project/assets/120647862/69d2b853-fa69-4190-a160-9350bbce4749)

For the next features, with respect to price range it is mobile depth and mobile weight, in this graph mobile weights are divided into 3 categories and they are showing the trend of price range w.r.to mobile depth that is mobile thickness and it clearly shows negative trend. So thinner mobiles are expensive as it is more comfortable and primarily the manufacturing company has to fit components in smaller size now. 

![image](https://github.com/jaydeepjadav/Mobile-Phone-Price-Prediction-Classification-Project/assets/120647862/ccb71f78-a301-45af-baf0-b27a94b2a6dc)

### Conclusion

From EDA we can see that here are mobile phones in 4 price ranges. The number of elements is almost similar. 

RAM have very much influence over price range.

Price decreases with increase in screen width.

3g also have significant impact on price range.

Costlier phones are lighter.

From all the model implementaions we can conclude that logistic regression and SVM we got the best results.
