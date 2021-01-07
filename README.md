# fantasy-bookstore

This is a small application for storing fantasy books I want to read or have already read but with some insecure features...


## Running Application

```bash
# Build and run Springboot application (http://localhost:8080)
./gradlew bootRun
```

## Endpoints

| Name                     | Endpoints                           | Parameter Name (Type) |
| :----------------------- | :---------------------------------- | :-------------------- |
| Get all Books            | http://localhost:8080               | N/A                   |
| Get Books by name        | http://localhost:8080?name=Hobbit   | `name` (`String`)     |
| Get Books by author      | http://localhost:8080?author=Martin | `author` (`String`)   |
| Get Books if read or not | http://localhost:8080?read=false    | `read` (`Boolean`)    |
