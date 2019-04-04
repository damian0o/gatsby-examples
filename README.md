# Run application

### Development mode

In gatsby-examples perfrom commands listed below:

* start mongodb
      
      make mongo-start 

* start server
    
      cd server 
      npm run start

To verify if everything is working as expected perform http request

    > http http://localhost:3000/tasks         

    HTTP/1.1 200 OK
    Connection: keep-alive
    Content-Length: 2
    Content-Type: application/json; charset=utf-8
    Date: Thu, 04 Apr 2019 05:49:12 GMT
    ETag: W/"2-l9Fw4VUO7kr8CvBlt4zaMCqXZ0w"
    X-Powered-By: Express

    []
