# Professional Networking Application

## Description
This project was developed as part of the course project for EE465 (Cryptocurrency and Blockchain Technology). The motivation for the project was to use blockchain to make a decentralised app for professional networking.

You will be redirected to a signup page if you are accessing this link for the first time. After signup, wait for the transaction to confirm and then again access the above link.

## Features
* Every user has a `Profile` page which shows the details of the user:
  - Image
  - UserId (unique)
  - Email-id
  - Bio
  - Experiences, Projects, Skills etc.
* User can change his/her details or add new projects using the `Edit Profile` page
* User can add user-id of other user as verifier for any experience, project or skill he has mentioned on his profile. The other user receives the verification request
* User can see verification request sent to them on the `Verify` page. They have the option to verify or decline it.
* The verifier who have accepted the request are shown with a `tick` in a list of verifiers.
* User can use the `Search` bar to see the profile page of other users.
* On the profile page of other users there is a `plus` symbol with the name which can be clicked to connect the user.
* All the connections can be seen in the `Connections` page.

## Setup
If you want to setup this project for development purposes, proceed as follows:
1. Change blockchain host and port in truffle-config.js  
2. Run ```truffle migrate --reset```  
3. Run ```npm run dev```
