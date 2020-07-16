# deno-app-test

## CRUD SAMPLE API WITH DENO

> Server will start on port 3000
```bash
deno run --allow-read --allow-net app.ts
```

## Routes

Method | Route | Description
------------ | ------------- | -------------
GET | http://localhost:3000/books | Returns all books
GET | http://localhost:3000/books/:id | Returns the book of the selected id
POST | http://localhost:3000/books | Create new book
DELETE | http://localhost:3000/books/:id | Deletes the book of the selected id
