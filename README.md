# REST API with Node.js, Mongoose & TypeScript

Note: This repository includes the [postman collection for the finished API](postman_collection.json)

#### Generate new keys: https://travistidwell.com/jsencrypt/demo/

#### Base64 encode the keys: https://www.base64encode.org/

## Technologies

-   Node.js
-   MongoDB with Mongoose
-   TypeScript
-   Express.js & Express.js middleware
-   Zod validation
-   JWT with refresh tokens

## Project structure

1. Bootstrap application
    1. Setup express JS
    2. Create routes function
    3. Setup database connection
    4. Setup logger
    5. Validate request middleware
2. Registration
    1. Create user model
    2. Create user endpoint
    3. Create user session
    4. Deserialize user middleware (refresh tokens)
    5. Get sessions
    6. Delete session
    7. Require user middleware
3. Product resource
    1. Create product model
    2. Create product
    3. Read product
    4. Update product
    5. Delete product

## Used for deployment

-   Docker (image)
-   docker-compose (container)
-   Caddy - Web server
-   DigitalOcean

Note: You will need Docker installed locally if you want to test your Docker configuration
