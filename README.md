The Hall Booking API allows users to manage the booking of halls for events or gatherings.

It's developed using by NodeJs, ExpressJs.

```
View all available rooms
```
```
Get/rooms/all
Get - http://local:3000
```
```
Create a New room:
POST/rooms/create
POST - {{base_url}}/rooms/create
```
```
Book a hall:
POST/booking 
POST - http://localhost:3000/booking
```

```
View all rooms with booked data:
GET/Viewbooking
GET-http://localhost:3000
```
```
View customers with booking:
GET/customers
GET-http://localhost:3000/customers
```
```
No of times Customer Booked:
GET/customers/:customerName
GET-http://localhost:3000/customers/:customerName
```
