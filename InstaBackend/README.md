# Instagram Backend Project using MVC Model in Java with Spring Boot

The Instagram Backend project is a web application built using the Model-View-Controller (MVC) architectural pattern in Java with Spring Boot. It provides backend functionality for an Instagram-like social media platform, including user authentication, posting images, following/unfollowing users, and interacting with posts.

## Prerequisites

Before running the application, ensure you have the following installed:

- Java Development Kit (JDK) 17
- Apache Maven
- MySQL database

## Technologies Used

- Java
- Spring Boot
- MySQL (as the database)

## Setup Instructions

1. **Clone the repository**

   ```bash
   git clone https://github.com/ahmedraza6377/WeeklyTest/tree/32a1c18a686b6bb5a13ed7fb6af0c9dcf6f0943d/weeklytest-7/InstaBackend/src/main/java/com/geekster/InstaBackend
   cd instagram-backend




## Framework and Language
> * SpringBoot
> * Java-17

## Dataflow
> * Controllers
* UserController class this class handled all tha api request using diffrents type of mapping annotations sign up,sign in ,create post etc.
* AdminController class this class handled all tha api request using diffrents type of mapping annotations sign up,sign in ,create post etc. 
> * Services
* Service classes in these classes I create all the method who provide all the business logic
* service
* hashingUtility
* AdminService.java
* AuthenticationService.java
* CommentService.java
* FollowService.java
* LikeService.java
* PostService.java
* UserService.java
> * repository
* repository classes in these classes I connect with CrudRepository for doing crud Operation on entities
* IAdminRepo.java 
* IAuthenticationRepo.java
* ICommentRepo.java
* IFollowRepo.java
* ILikeRepo.java
* IPostRepo.java
* IUserRepo.java
> * Database Design
* I Used mysql DataBase

## DataStructure
* ArrayLits etc.


## Project Summary
> this is a simple instagram backend web application in this application sign up user sign in user at diffrent level admin,user user can create post like reels , photos etc and other user cal like these post as well for creating post user must be sign in in this application i uesd authentication for user priavcy i used uuid for authentication
> I also used dependency like spring web,lombok,mysql,swagger, validation etc.


