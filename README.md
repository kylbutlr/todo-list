# Todo List (API)

Todo List application RESTful API node server

Created to be used with my [Todo List (React)](https://github.com/kylbutlr/todo-list-react) app front-end

Features: REST CRUD, routing, and tests

Uses: PostgreSQL, Express, and Jest

***

### [Click here for a live preview](https://kylbutlr-todos-react.herokuapp.com/) of my React app that uses this API.

Or [go to the API directly](https://kylbutlr-todos-api.herokuapp.com/todos) in your browser. (Link goes to /todos)

This is currently a "public app" without user accounts, so **all entries and modifications will be publicly displayed (deleted daily)**.

***

## Install

```shell
npm install
```

## Usage

Start the local server:

```shell
npm start
```


| HTTP   | Request    | Response                            |
| ------ | ---------- | ----------------------------------- |
| GET    | /todos     | Returns all todos                   |
| GET    | /todos/:id | Returns one todo selected by the ID |
| POST   | /todos     | Creates a new todo                  |
| PUT    | /todos/:id | Edits a todo selected by the ID     |
| DELETE | /todos     | Deletes all todos                   |
| DELETE | /todos/:id | Deletes one todo selected by the ID |

#### Tests:

Start unit and integration tests:

```shell
npm test
```

***

## Contributing

[@kylbutlr](https://github.com/kylbutlr)

#### Special Thanks: 

[@NoumanSaleem](https://github.com/NoumanSaleem)

## License

MIT
