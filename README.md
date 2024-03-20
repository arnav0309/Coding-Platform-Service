# problem setting service




## How routing is working in this project
 - /api/v1/problems/ping
    - because the routes starts with /api
        /api     -> /v1    ->/problems    ->/ping
        apiRouter --> v1Router --> problemRouter --> problemControllers --> service layer
