# FastAPI example API

### Start server:
`$ uvicorn sql_app.main:app --reload`

### Access API docs:
```
Go to http://127.0.0.1:8000/docs in browser
```

### Call API:
`$ curl -X POST "http://127.0.0.1:8000/users/" -d '{"email":"bar@foo.com", "password":"baz"}'`


Taken straight from the fantastic docs at https://fastapi.tiangolo.com/tutorial/sql-databases/