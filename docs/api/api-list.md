# First API List

## Auth

POST /api/auth/register  
POST /api/auth/login  
POST /api/auth/forgot-password  
POST /api/auth/verify-otp  
POST /api/auth/reset-password  
GET /api/auth/me  
POST /api/auth/logout  

## Roles

GET /api/roles  
POST /api/roles  

## Permissions

GET /api/permissions  
POST /api/permissions  

## Departments

GET /api/departments  
POST /api/departments  
PUT /api/departments/:id  
DELETE /api/departments/:id  

## Employees

GET /api/employees  
POST /api/employees  
GET /api/employees/:id  
PUT /api/employees/:id  
DELETE /api/employees/:id  

## Attendance

POST /api/attendance/check-in  
POST /api/attendance/check-out  
GET /api/attendance/today  
GET /api/attendance/report  

## Clients

GET /api/clients  
POST /api/clients  
GET /api/clients/:id  
PUT /api/clients/:id  
DELETE /api/clients/:id  