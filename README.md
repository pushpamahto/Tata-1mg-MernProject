# Tata-1mg-MernProject

<h1 align="center">Tata 1mg Clone</h1>
<h3 align="center">It's a MERN Stack healthcare web application with all the major functionalities</h3>

<br/>

<h2 align="center">🖥️ Tech Stack</h2>

<h4 align="center">Frontend:</h4>
<p align="center">
  <img src="https://img.shields.io/badge/React (18.2.0)-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="reactjs" />
  <img src="https://img.shields.io/badge/Redux (4.2.0)-593D88?style=for-the-badge&logo=redux&logoColor=white" alt="redux" />
  <img src="https://img.shields.io/badge/Chakra%20UI (2.2.8)-3bc7bd?style=for-the-badge&logo=chakraui&logoColor=white" alt="chakra-ui" />
  <img src="https://img.shields.io/badge/Firebase (9.9.3)-20232A?style=for-the-badge&logo=firebase&logoColor=ffcd33" alt="Firebase" />
  <img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" alt="javascript" />
  <img src="https://img.shields.io/badge/Rest_API-02303A?style=for-the-badge&logo=react-router&logoColor=white" alt="restAPI" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="css3" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="html5" />
</p>
<h4 align="center">Backend:</h4>

<p align="center">
  <img src="https://img.shields.io/badge/Node.js (16.14.2)-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="nodejs" />
  <img src="https://img.shields.io/badge/Express.js (4.18.1)-000000?style=for-the-badge&logo=express&logoColor=white" alt="expressjs" />
  <img src="https://img.shields.io/badge/MongoDB (6.0)-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" alt="mongodb" />
</p>

<h4 align="center">Payment Gateway:</h4>

<p align="center">
  <img src="https://img.shields.io/badge/instamojo--nodejs-(0.0.5)-blue?style=for-the-badge&logo=instamojo&logoColor=white" alt="Instamojo" />
</p>



<h3 align="center"><a href="https://tata1mg-clone-nem201.vercel.app/"><strong>Want to see live preview »</strong></a></h3>

Tata 1mg is India’s leading consumer health platform. It provides services, including e-pharmacy, diagnostics, e-consultation and health content.



<br/>

## 🚀 Features

-   Login and Signup Page with mobile OTP
-   Firebase Authentication
-   Product Filters Based on Brand and Discount
-   Product Sorting Based on Price, Rating
-   Product Filtering and Sorting works together
-   Cart Add and Remove Items
-   Cart Update Quantities
-   Address Management
-   Order Summary
-   Instamojo Payment Gateway


## Screenshots

### Homepage -

This is the main landing page of our website. Here, if you clicked on any navigation then you will redirect to respective page. Also, we have added searching of product option with debouncing feature.

All pages are responsive.

![homepage](https://github.com/user-attachments/assets/c9939bce-71f7-4f53-a7bb-8781c110a842)


### Sign up / Sign in Page -

On this page, you can register a user. If the user is already registered, you can simply sign in by providing valid details of the user. We have used `Firebase Authentication` so, once you entered your mobile number you will get `OTP`, you need to enter that `OTP`.

![Sign In](<img width="894" alt="login" src="https://github.com/user-attachments/assets/99b9dd4d-21c5-45b7-a436-ef7b2e1fff85">


### Search Functionality

If you type any `keyword` the list of product will appear in the modal component. You can add it to cart directly from here or you can see more details by clicking on the product.
We have added debouncing functionality on searching products.

![search](https://github.com/user-attachments/assets/e0bf0b00-565f-4fae-bbde-be4bd1993817)

### Products Page -

Here users can browse, `filter` the product based on `brand and discound`, `sort` by `price or rating`, filter and sort will work togather and add items to the cart by clicking on the `Add to Cart` button.

![product](https://github.com/user-attachments/assets/239957e6-6c99-45f3-a746-bb3af79b50da)


### Cart Page -

Here all the products added to the cart will be shown. On this page, you can `remove` the item from cart and also, `increase` or `decrease` count. By clicking on the `CHECKOUT` button you will be redirect to the checkout page.

![cart](https://github.com/user-attachments/assets/5987c37c-e31d-4c8a-afb0-ecd634793843)


### Order Summary Page -

On this page you will see all details like, address, total bill, shipping address. By clicking on `Proceed to payment` button you will be redirect to payment page.

![ordersummary](https://github.com/user-attachments/assets/90d3e579-5b41-47a2-96fa-1c5aa9e130e9)


### Payment Page -



![payment](https://github.com/user-attachments/assets/82e9e59d-6184-4d2e-a4b4-ef772565038a)


### Payment Status

After submitting the payment details you will get `Payment Successful` or `Payment Failed` depending on the `status of the payment`. Also, you received mail of bill details of order.

## Payment Successful

![paymentsuccessful](https://github.com/user-attachments/assets/012cc2f6-298d-4491-b37b-a3e98f7aeb96)


## Payment failed

![paymentfailed](https://github.com/user-attachments/assets/e34188d8-a075-42b9-bb1c-777ca6326e73)


