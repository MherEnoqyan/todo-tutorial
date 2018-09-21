## Installation

```
git clone https://github.com/MherEnoqyan/todo-tutorial.git
cd todo-tutorial/backend
npm install
cd ../frontend
npm install
cd ../
npm install
```

## Configuration DB

Make the appropriate changes in the backend/server.js file

```
mongoose.connect(‘mongodb://<dbuser>:<dbpassword>@<host>:<port>/<database>’)
```

## Run

```
npm start
```

By default the API server starts on port 3000, http://localhost:3000.

