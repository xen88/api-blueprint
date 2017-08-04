FORMAT: 1A

# All Endpoints
Get a list of all the configured REST endpoints.

# GET http://app.spportme.com/api/all
+ Response 200 (text/plain)
```
        {
          "info": "Below are a list of all the GET API endpoints (read the info response for explanation):",
          "a": "/api/users/players",
          "b": "/api/users/admin",
          "c": "/api/clubs",
          "d": "/api/events",
          "e": "/api/events/:id",
          "f": "/api/accolades",
          "g": "/api/accolades/:id",
          "h": "/api/experience",
          "i": "/api/experience/:id",
          "j": "/api/userdata/:id",
          "k": "/api/userdataid"
        }
```
