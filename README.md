# problem setting service

To set up the project on your local machine do the following steps:
1. Clone the project
2. Go inside the downloaded folder and install node modules
3. Create a new .env file in the root directory and set the env variables
4. Start the backend server


## How routing is working in this project
 - /api/v1/problems/ping
    - because the routes starts with /api
        /api     -> /v1    ->/problems    ->/ping
        apiRouter --> v1Router --> problemRouter --> problemControllers --> service layer
