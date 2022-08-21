# Simple Go API

A simple go API Rest made by following go docs


## Reference

 - [Developing a RESTful API with Go and Gin](https://go.dev/doc/tutorial/web-service-gin)
 - [Go Docs - Get Started](https://go.dev/learn/)


## Running Locally

Clone the project

```bash
  git clone https://github.com/FabioRocha231/go_simple_api
```

Enter the project directory

```bash
  cd go_simple_api
```

Install the Dependencies

```bash
  go get .
```

Start the Server

```bash
  go run .
```


## API Documentation

#### Return all albums

```http
  GET http://localhost:8080/albums
```

#### returns an specific album

```http
  GET http://localhost:8080/albums/:id
```
| Query   | Type  | Description
| :-----  | :----- | :---------- |
| `:id`    | `number` | **Mandatory** |

#### Create a item

```http
  POST http://localhost:8080/albums
```

| Parameter   | Type       | Description                                   |
| :---------- | :--------- | :----------- |
| `id`      | `number` | **Mandatory** |
| `title`   | `string` | **Mandatory** |
| `artist`  | `string` | **Mandatory** |
| `price`   | `number` | **Mandatory** |
