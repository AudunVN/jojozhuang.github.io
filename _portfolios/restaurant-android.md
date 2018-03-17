---
layout: portfolio
key: portfolio
title: "Restaurant(Anroid)"
index: 90
tags: [Android, Java, Android Studio, Genymotion]
image: /public/portfolios/restaurantandroid/thumbnail.png
excerpt: An Android App for searching restaurants, built with Java.
category: mobile
---

> An Android App for searching restaurants, built with Java.

This app is used to search restaurants, view the details of them. After login, you can share your experience with others about the restaurant you have been. You can submit ratings and reviews. All of the data are dynamic, which means this app connects backend server to retrieve data.

## 1. Restaurant List
### 1.1 Home screen  
This is the list of restaurants. Each restaurant has a specific icon based on its category. Restaurants are grouped to 5 categories:
* Restaurant
* Dessert
* CoffeeTea
* Bakeries
* IceCream

![index](/public/portfolios/restaurantandroid/index.png){:width="400px"}  
Touch on one row, restaurant Detail will be displayed.
### 1.2 Detail Screen
Pictures, address, rating and comments show up. If you have signed in, you are able to submit ratings and add comments to share your experience.  
![detail](/public/portfolios/restaurantandroid/detail.png){:width="400px"}  
1) You can change the rating value of this restaurant by touching on the rating bar. The new value will be submitted to server directly.  
2) Click on the ‘Write Comment’ button. User name is displayed at the top of the screen. The new comment will be submitted to server after clicking ‘Submit’ button.
![detail](/public/portfolios/restaurantandroid/submitreview.png){:width="400px"}  

## 2. Searching
In the restaurant list view screen, click the ‘Search’ button on the menu bar.
![searchbutton](/public/portfolios/restaurantandroid/searchbutton.png){:width="400px"}  
Input the keyword you want to search, press Enter. The list will be refreshed with new result.
![search](/public/portfolios/restaurantandroid/search.png){:width="400px"}  

## 3. User Function
Register as new user.
![signup](/public/portfolios/restaurantandroid/signup.png){:width="400px"}  
Though it is not necessary to sign in to use this app, you have to login first if you want to submit rating or review.
![signin](/public/portfolios/restaurantandroid/signin.png){:width="400px"}  

## 4. View in Landscape Mode  
Rotate the screen to landscape mode, the layout still looks pretty.
![landscape](/public/portfolios/restaurantandroid/landscape.png){:width="700px"}  
## 5. View in Tablet
Large Screen size is supported by default. The biggest difference is that the details screen is displayed along with the list view screen. You are able to see all of the contents on one screen.
![pad](/public/portfolios/restaurantandroid/pad.png){:width="900px"}  
If you change the rating value at the right side, you will see the effect at the left side immediately.
![pad2](/public/portfolios/restaurantandroid/pad2.png){:width="900px"}  

## 6. RESTful Services
The backend data server is built with ASP.NET MVC, which provides RESTful APIs. You can simulate the register, login and logout function here. And four main APIs are available.
* Get restaurant list
* Get restaurant by id
* Set rating
* Set comments

![backend](/public/portfolios/restaurantandroid/backend.png)  
## 7. Source Files
* [Source files of Restaurant on Github](https://github.com/jojozhuang/Portfolio/tree/master/Restaurant/Android)
* [Source files of Data Server on Github](https://github.com/jojozhuang/Portfolio/tree/master/Restaurant/DataServer)
