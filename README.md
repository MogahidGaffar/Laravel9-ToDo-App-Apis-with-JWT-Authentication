
<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="#">
    <img src="https://github.com/MogahidGaffar/laravel9_ToDoApp_jwt_Api_authentication/blob/main/public/imgs/laravel_jwt.png" alt="Logo" >
  </a>

  <h3 align="center">To-Do Api endpoints using JWT auth in laravel  </h3>


</div>



## What is Rest API?
The REST API (also known as the RESTful API) is an application programming interface (API or web API) that follows the specifications of the REST architecture style and enables interaction with RESTful web services. REST stands for Representative State Transition and was developed by the computer scientist Roy Fielding.


##  When should you use JSON Web Tokens?
Here are some scenarios where JSON Web Tokens are useful:
<h5>
1. Authorization: This is the most common scenario for using JWT. Once the user is logged in, each subsequent request will include the JWT, allowing the user to access routes, services, and resources that are permitted with that token. Single Sign On is a feature that widely uses JWT nowadays, because of its small overhead and its ability to be easily used across different domains.
</br>
2. Information Exchange: JSON Web Tokens are a good way of securely transmitting information between parties. Because JWTs can be signed—for example, using public/private key pairs—you can be sure the senders are who they say they are. Additionally, as the signature is calculated using the header and the payload, you can also verify that the content hasn't been tampered with. </br>
</h5>


###  Whats this app provide ?

* Login api endpoint.
* Register api endpoint.
* Logout api endpoint.
* Create to-do api endpoint.
* Update to-do api endpoint.
* Show to-dos api endpoint.
* Delete to-do api endpoint.


##  Built With

* Laravel
* Bootstrap
* Baldes
* Mysql DB

#### Register Endpoint 

<img src="https://github.com/MogahidGaffar/laravel9_ToDoApp_jwt_Api_authentication/blob/main/public/imgs/1.PNG" />

#### Login Endpoint 

<img src="https://github.com/MogahidGaffar/laravel9_ToDoApp_jwt_Api_authentication/blob/main/public/imgs/2.PNG" />


#### Logout Endpoint 

<img src="https://github.com/MogahidGaffar/laravel9_ToDoApp_jwt_Api_authentication/blob/main/public/imgs/3.PNG" />


#### Create To-Do  Endpoint 

<img src="https://github.com/MogahidGaffar/laravel9_ToDoApp_jwt_Api_authentication/blob/main/public/imgs/4.PNG" />

#### Show All To-Dos  Endpoint 

<img src="https://github.com/MogahidGaffar/laravel9_ToDoApp_jwt_Api_authentication/blob/main/public/imgs/5.PNG" />

#### Show single To-Dos  Endpoint 

<img src="https://github.com/MogahidGaffar/laravel9_ToDoApp_jwt_Api_authentication/blob/main/public/imgs/6.PNG" />

#### Update To-Do Endpoint

<img src="https://github.com/MogahidGaffar/laravel9_ToDoApp_jwt_Api_authentication/blob/main/public/imgs/7.PNG" />

#### Delete To-Do Endpoint 

<img src="https://github.com/MogahidGaffar/laravel9_ToDoApp_jwt_Api_authentication/blob/main/public/imgs/8.PNG" />



<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.


### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app

 1. Clone the repo
   ```sh
 gh repo clone MogahidGaffar/laravel9_ToDoApp_jwt_Api_authentication
   ```
2. Install NPM packages
   ```sh
   npm install
   ```
3. composer update
   ```sh
   composer update
   ```

3. Database Migrattion
   ```sh
   php artisan migrate
   ```
 
3. Server establish
   ```sh
   php artisan serve
   ```


## Contact

Mogahid Gaffar -  mogahidgaffar@gmail.com


