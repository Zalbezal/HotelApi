# HotelApi
hotel api section of Anthony GG's full time go dev


# Hotel reservation backend

## Project outline
- users -> book froom from a hotel
- admins -> going to check reservation/bookings
- Authentication and Authorization -> JWT tokens 
- Hotels -> CRUD API -> JSON
- Rooms -> CRUD API -> JSON
- Scripts -> database management -> seeding, migrations

## Resources
### Mongodb driver
Documentation
```
https://mongodb.com/docs/drivers/go/current/quick-start
```

Installing mongodb client
```
go get go.mongodb.org/mongo-driver/mongo
```

### gofiber
Documentation
```
https://gofiber.io
```

Installing gofiber
```
go get github.com/gofiber/fiber/v2
```

## Docker
### Installing mongodb as a docker container
```
docker run --name mongodb -d mongo:latest -p 27017:27017
```