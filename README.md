# Student-REST-API-Testing

## How to run this project
- Clone this project
- Open with Postman / Command Shell
- Run Command:  
```console 
newman run Booking.postman_collection.json -e Booking-en.postman_environment.json 
```
- Run Command for Report: 
```console 
newman run Booking.postman_collection.json -e Booking-en.postman_environment.json -r cli,htmlextra
```

## Technology used:
- Postman
- Newman

## Prerequisite:
- Jdk
- Node Js
- Newman
- Html Report Library

## Newman and Report Installation Process:
- Newman Install Command:
```console
npm install -g newman
```
- Newman Html Report Install Command:
```console
npm install -g newman-reporter-htmlextra
```

## API Documentation:
- https://documenter.getpostman.com/view/27187339/2s93ebUWmr

## Test case list:
1. ### Get Student
	> In this section we checked the whole pre-defined datasets of students and validate the following test result:
	1. > Status Code

2. ### Create Student
	> In this section we created a dataset giving information in the request body and validate the following test result:
 	1. > Status Code

3. ### Get Specific Student
  	> In this section called a specific student using his/her id and validate the following field values:
  	1. > Status Code
 	2. > ID
 	3. > First Name
 	4. > Middle Name
 	5. > Last Name
 	6. > Date of Birth

4. ### Create Technical Skills
	> In this section we added technical skills of the student by calling his/her id and validate the following test result:
 	1. > Status Code
	
5. ### Create Student Address
	> In this section we added the address of the student by calling his/her id and validate the following field values:
	1. > Status Code
 	2. > Status
 	3. > Message

6. ### Final Student Details
	> In this section we called the student using his/her id and validate the following field values:
	1. > Status Code
 	2. > Language
	3. > Year of Experience
	4. > House Number
	5. > City
	6. > Country
	7. > Mobile
	8. > Current Address

## Newman Report Summary:
![4](https://github.com/Mahim-Hasan/Student-REST-API-Testing/assets/77658882/a47ac4ae-a243-485e-81ec-cb32a93ad170)
![5](https://github.com/Mahim-Hasan/Student-REST-API-Testing/assets/77658882/164672d9-e3fb-4c0a-8352-b24c5b082d1e)