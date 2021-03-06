# Vehicool Backend

## DESCRIPTION
This is an API programs for vehicool, this programs can process data in vehicool database by access some endpoints. The endpoints provided to access vehicles, categories, users, and histories.
## INSTALLATION
#### 1. Clone Repository
```
git clone https://github.com/aviantofan/vehicool-backend
```
#### 2. Import Database vehicle_rent.sql

#### 3. Configure ENV
#### 4. Install Package
```
npm i
```
#### 5. Run Apps
```
npm run start
```
```
npm run dev
```
## ENDPOINT
#### Auth Endpoint|
| METHOD | API | REMARKS |
| :-------------: |:-------------:|:-----------:|
| ```POST``` | /auth/register | Register account |
| ```POST``` | /auth/login | Login account|
| ```POST``` | /auth/forgotPassword | Reset password|

#### Vehicles Endpoint|
| METHOD | API | REMARKS |
| :-------------: |:-------------:|:-----------:|
| ```GET``` | /vehicles | Get all data vehicle|
| ```GET``` | /vehicles?search=xx | Get all data vehicle by search|
| ```GET``` | /vehicles/p/populars | Get data vehicle populars|
| ```GET``` | /vehicles?page=xx&limit=xx | Get all data vehicle with page and limit| 
| ```GET``` | /vehicles?sort=xx&order=xx | Get all data vehicle with sort and order| 
| ```GET``` | /vehicles/:id | Get data vehicle by id |
| ```POST``` | /vehicles | Create data vehicle|
| ```PATCH``` | /vehicles/:id | update data vehicle by id|
| ```DELETE``` | /vehicles/:id | delete data vehicle by id|

#### Categories Endpoint|
| METHOD | API | REMARKS |
| :-------------: |:-------------:|:-----------:|
| ```GET``` | /categories | Get all data category|
| ```GET``` | /categories?search=xx | Get all data category by search|
| ```GET``` | /categories?pagexx&limit=xx | Get all data category with page and limit|
| ```GET``` | /categories/:id | Get data category by id |
| ```POST``` | /categories | Create data category|
| ```PATCH``` | /categories/:id | update data category by id|
| ```DELETE``` | /categories/:id | delete data category by id|

#### Users Endpoint|
| METHOD | API | REMARKS |
| :-------------: |:-------------:|:-----------:|
| ```GET``` | /users?search=xx | Get all data user by search |
| ```GET``` | /users?pagexx&limit=xx |Get all data user with page and limit|
| ```GET``` | /users | Get all data User|
| ```GET``` | /users/:id | Get data user by id |
| ```POST``` | /users | Create data user|
| ```PATCH``` | /users/:id | update data user by id|
| ```DELETE``` | /users/:id | delete data user by id|

#### Profile Endpoint all data |
| METHOD | API | REMARKS |
| :-------------: |:-------------:|:-----------:|
| ```GET``` | /profile | Get current active user|

#### History Endpoint
| METHOD | API | REMARKS |
| :-------------: |:-------------:|:-----------:|
| ```GET``` | /histories/vehicles/createdAt| Get all data popular based on month|
| ```GET``` | /histories | Get all data vehicle|
| ```GET``` | /histories?search=xx | Get all data by search|
| ```GET``` | /histories?pagexx&limit=xx | Get all data with page and limit|
| ```GET``` | /histories/:id | Get data history by id|
| ```POST``` | /histories | Create data history|
| ```PATCH``` | /histories/:id | update data history by id|
| ```DELETE``` | /histories/:id | delete data history by id|

## BACKEND DEPLOYMENT
```
https://vehicool-backend.herokuapp.com/
```