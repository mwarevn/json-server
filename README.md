### Small Tool for json-server

### Installation

- Just, run this command: -
  ```
  git clone https://github.com/mwarevn/json-server.git && mv json-server/json-server start
  ```


#### And then in file package.json

- change:

```
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
```


- to:

```
"scripts": {
    "start": "bash start",
    "test": "echo \"Error: no test specified\" && exit 1"
  },
```
