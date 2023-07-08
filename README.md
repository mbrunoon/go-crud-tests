# Newsfeed simple Rest API + Tests

Simple CRUD with some automated Tests.

Tutorial: [REST API with Go / Gin + Some Simple Tests](https://www.youtube.com/watch?v=LOn1GUsjOF4) by [DavidAlsh](https://www.youtube.com/@DavidAlsh)

To start the server run:

```
make dev
```

## Endpoints

| Route | Method | Description | Expected Status |
|:--|:--:|:--:|:--:|
| /newsfeed | POST | Create a Item| 204 |
| /newsfeed | GET | Retrieve a list of Items| 200 |

## Tests

**Commands:**

- `go test ./...`: execute all tests
- `go test -cover ./...`: execute the tests and show the % coverage from them

### References: 
- **Using Makefile**: https://opensource.com/article/18/8/what-how-makefile