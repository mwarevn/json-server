# Small Tool for [json-server](https://github.com/typicode/json-server#getting-started)

## Installation

### Just, run this command


```
npm init
```

 * Press Enter to skip the setup steps

```
npm install -g json-server
```

```
git clone https://github.com/mwarevn/json-server.git && mv json-server/json-server start
```


### And then in the file package.json

#### -- change:

```
"scripts": {
  "test": "echo \"Error: no test specified\" && exit 1"
},
```


#### -- to:

```
"scripts": {
  "start": "bash start",
  "test": "echo \"Error: no test specified\" && exit 1"
},
```
