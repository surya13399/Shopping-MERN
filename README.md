# Shopping eCommerce Application


## Features

- Full featured shopping cart
- Product pagination
- Product search feature
- User profile with orders
- Admin product management
- Admin user management
- Checkout process (shipping, payment method, etc)
- PayPal / credit card integration


### Env File

```
NODE_ENV = development
PORT = 5000
MONGO_URI = your mongodb uri
JWT_SECRET = 'abc123'
PAYPAL_CLIENT_ID = your paypal client id
```

### Seed Database

You can use the following commands to seed the database with some sample users and products as well as destroy all data

```
# Import data
npm run data:import

# Destroy data
npm run data:destroy
```

```
Sample User Logins

admin@example.com (Admin)
123456

surya@example.com (Customer)
123456

ravi@example.com (Customer)
123456
```

