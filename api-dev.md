## API Dev

* It is helpful to use a tool like Postman to send http requests. 
* For api endpoints requiring auth, add `hanaauthtoken` and `hanauserid` as headers. You can get the values for these headers by making a POST request to `/api/users/login` with your `email` and `password` values in the body of the request. 
