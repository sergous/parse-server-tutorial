# Parse Express Server
Basic server setup with [parse-dashboard](https://github.com/parse-community/parse-dashboard).

## Install
```
npm start:db
npm start
```

## Client todo app
You should have Todo class created in parse server.
```JavaScript
const Todo = new Parse.Object('Todo');
Todo.set('title', 'Todo').set('isDone', false);
await Todo.save();
```
Code: [parse-todo-app](https://github.com/sergous/parse-todo-app)

## Credits
Code: [parse-community/parse-server](https://github.com/parse-community/parse-server)
