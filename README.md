# Online 3C Transaction Platform
3C平台交易系統



# Abstract
This work aims to prepare a platform for seller and shopper in 3C transaction. In this system, we have the security of login features for both shopper and seller, which provides them the security of transaction. Also, seller can add the product in any time and shopper can check for their personal shipping information in any time. The platform provides the opportunity for both shopper and seller to have a chance for security transaction.



# Purpose of Creation
In order to increase the speed of 3C product transaction, online shopping systems have become the mainstream nowadays. Therefore, we tried to build up a shopping systems that can help seller and shopper to have a chance to transact online. By using the system, both shopper and seller can get benefit for choosing/buying products in a more convenient way. In addition to the traditional face-to-face transaction, Online 3C Transaction Platform can provides you a more security and faster way to buy and sell a product.



# Features
[Seller]
1. Login/Logout the systems to activate/deactivate their privileges of managing their products.
2. After login into the systems, seller can add a new selling products in their account.
3. People can also sign up to become a new seller after filling up some personal information.

[Shopper]
1. Login/Logout the systems to activate/deactivate their privileges of previewing products and shopping.
2. Shopper can check the detail of each product to determine whether buying it.
3. Shopper can manage their shopping cart and the system will help create an order after shopper's confirm.
4. After sending out the order, system will automatically send an email to shopper's mailbox to make sure that the order is correct.

# Introduction
Step.01  Enter the welcome page for the Online 3C Transaction System

![](C:\htdocs\finalproject\images\introduction\image01.png)



**[Seller]**

Step.02	Click up **Seller** button, enter the seller login page. If you are not a seller yet, please sign up first.

![](C:\htdocs\finalproject\images\introduction\image02.png)



Step.03	Sign up for a new seller and fill in some personal information.

![](C:\htdocs\finalproject\images\introduction\image03.png)



Step.04	After sending out the request, you can login with your new account.

![](C:\htdocs\finalproject\images\introduction\image04.png)



Step.05	After login into the seller interface, we can start adding products to sell.

![](C:\htdocs\finalproject\images\introduction\image05.png)

If we want to login as a shopper, we have to logout our seller account first.



**[Shopper]**

Step.06	Go back to the welcome page, and click the **Shopper** button. You can enter the shopper login page. If you are not a shopper yet, please sign up first.

![](C:\htdocs\finalproject\images\introduction\image06.png)



Step.07	Sign up for a new shopper and fill in some personal information.

![](C:\htdocs\finalproject\images\introduction\image07.png)



Step.08	After sending out the request, you can login with your new account.

![](C:\htdocs\finalproject\images\introduction\image08.png)



Step.09	After login into the shopper interface, we can check the selling products. The product we added before would also show up.

![](C:\htdocs\finalproject\images\introduction\image09.png)

In this page, we can check out the products using the features for searching in left two block, which includes:

- Search products using key words
- Search products using price range
- Search products using product category



Step.10	Let's check our the product detail and add a new product in our shopping cart.

![](C:\htdocs\finalproject\images\introduction\image10.png)

![](C:\htdocs\finalproject\images\introduction\image11.png)

We can always check the products and manage our shopping cart before checkout:

![](C:\htdocs\finalproject\images\introduction\image12.png)



Step.11	After confirming the order, we can send out our order with our shipping information.

![](C:\htdocs\finalproject\images\introduction\image13.png)



Step.12	Email Received.

![](C:\htdocs\finalproject\images\introduction\image14.png)



# Try to build up the system yourself

## 0. Initial Download  

- Official XAMPP (https://www.apachefriends.org/download.html)
- Download my GitHub codes (https://github.com/Jui-Yun/Shopping_Cart)



## 1. Setup MySQL Database

1. Go to the `/Shopping_Cart-main` folder, find the `finalproject.sql file`. Load the file into MySQL database as follows.

   ![](C:\htdocs\finalproject\images\introduction\image15.png)

   

2. Open the `/Shopping_Cart-main/connMysql.php` file, replace the `/* your database password */` comment and fill in with your database password.

   ![](C:\htdocs\finalproject\images\introduction\image16.png)

3. Open a browser and type in the URL http://localhost/finalproject/welcomepage.php, then you will receive the system.



# Additional

In order to activate the email sending feature, check the following references:

- https://blog.pulipuli.info/2013/07/xampp.html
- https://docs.bitnami.com/aws/apps/dolibarr/troubleshooting/send-mail/
