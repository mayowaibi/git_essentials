# MediaVault Wiki

Created by group 3 of EECS2311.

## Members 
* Isaac Ibidun
* Herman Lim
* Ruth Bezabeh
* Mate Korognai
* Muhammad Ehab Khan

## Table of Contents 
- [Description](#description)
- [Iteration 1](#review)
  - [Overview](#overview)
  - [Architecture](#architecture)
    - [Backend](#backend)
    - [Persistence](#persistence)
    - [User Interface](#user-interface)
- [Running MediaVault](#running-mediavault)

## Description
MediaVault is a software application with the main purpose of storing a collection of media, and allowing users to keep track of their progress in them. 

Users are able to securely create an account and login to it. Within the account, users have access to their own Media Vault where they can store movies and books. MediaVault provides a wide range of movies and books that users can add to their vault, with a search feature that makes it easy to find their desired media. With each movie and book in the vault, users can assign a status such as 'Completed', 'Currently Watching', and 'Yet To Watch'. This allows the user to keep track of media they have consumed.

MediaVault can also recommend movies and books to users based on their preferred genres and they are able to view information on each piece of media like reviews and ratings. In addition, users can personalize their profile by setting a user icon as well as adding a custom status to their profile. They can also view their user statistics such as 'Movies Watched' and 'Pages Read' so they have a better idea of their media consumption trends.

## Iteration 1 

### Overview 
For iteration 1, we created the login and sign up user interfaces and implemented the functionality of the skeletal structure of MediaVault.

### Architecture
![uml-diagram](https://cdn.discordapp.com/attachments/1075816196072554536/1075816562205917254/UML_Diagram.png)
The architecture of MediaVault is separated into 3 layers (packages) with classes and dependencies working together to create a functional application.

#### Backend
This is MediaVault. It is a piece of software with the main purpose of storing movies and books and allowing users to keep track of their progress in them. They will have an account that they create, and securely login to said account. Within the account, the user has access to their own Media Vault where they can store movies and books. They can select movies from a wide range of available ones. With each movie and book in the vault, the user can assign a status such as 'completed', 'currently watching', and 'dropped'. This allows the user to keep track of media they have consumed.

#### Persistence
This is MediaVault. It is a piece of software with the main purpose of storing movies and books and allowing users to keep track of their progress in them. They will have an account that they create, and securely login to said account. Within the account, the user has access to their own Media Vault where they can store movies and books. They can select movies from a wide range of available ones. With each movie and book in the vault, the user can assign a status such as 'completed', 'currently watching', and 'dropped'. This allows the user to keep track of media they have consumed.

#### User Interface
This is MediaVault. It is a piece of software with the main purpose of storing movies and books and allowing users to keep track of their progress in them. They will have an account that they create, and securely login to said account. Within the account, the user has access to their own Media Vault where they can store movies and books. They can select movies from a wide range of available ones. With each movie and book in the vault, the user can assign a status such as 'completed', 'currently watching', and 'dropped'. This allows the user to keep track of media they have consumed.

## Running MediaVault
To run MediaVault, simply compile and run the **MediaVault.java** file located in the userinterface package in the source folder.


