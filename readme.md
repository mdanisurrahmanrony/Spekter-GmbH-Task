### Env Variables

Create .env file inside the root folder and add your config variables `DATABASE` and `PORT` inside .env file. Here config variables `DATABASE` is `MongoDB Connection String in Application Code`.

### Install Dependencies

Run the following command for installing dependencies.

```
yarn
```

### Run Server

Run the following command for running the server.

```
yarn start
```

### Post Request

Post request to make order.

```
http://localhost:8000/api/createorder
```

### Get Request

Get request for order response

```
http://localhost:8000/api/getorders
```

### Sample Data

Sample JSON Data for Insert

```
{
    "orderItems": [
        {
            "quantity": 3,
            "product" : "Orange"
        },
        {
            "quantity": 2,
            "product" : "Banana"
        },
        {
            "quantity": 5,
            "product" : "Apple"
        }
    ],
    "phone": "+420702241333"
}
```
