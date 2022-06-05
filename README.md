## Spring Boot Microservice 2 - Transaction Service

### Endpoints

#### 1 -> Save Transaction

````
POST /api/transaction HTTP/1.1
Host: localhost:4444
Authorization: Basic base64(username:password)
Content-Type: application/json
Content-Length: 42

{
    "userId": 1,
    "productId": 1
}
````


#### 2 -> Get All Transaction of User 

````
GET /api/transaction/1 HTTP/1.1
Host: localhost:4444
Authorization: Basic base64(username:password)
````


#### 3 -> Delete Transaction

````
DELETE /api/transaction/2 HTTP/1.1
Host: localhost:4444
Authorization: Basic base64(username:password)
````