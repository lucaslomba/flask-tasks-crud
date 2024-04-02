
# 💰 Tasks with Flask

Task project for studying Python with Flask
## 🚀 Techs

Python, Flask


## 🛠️ Clone

To clone and run this application, you'll need Pytho installed on your computer.

📥 Clone the repository:

```bash
  git clone https://github.com/lucaslomba/flask-tasks-crud.git
```

📂 Navigate to the project directory:

```bash
  cd flask-tasks-crud
```

### Start project 

```bash
# Start server
$ python3 app.py

```

## API Reference

### Get all tasks

```http
  GET api_url/tasks
```
### Get task by ID

```http
  GET /api/tasks/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. |

### Add new task

```http
  POST /api/tasks
```

Request body

```JSON
{
    "title": "string",
    "description": "string"
}
```

### Update task by ID

```http
  PUT /api/tasks/${id}
```

Request body

```JSON
{
    "title": "string",
    "description": "string",
    "completed": true
}
```


### Delete task by ID

```http
  DELETE /api/tasks/${id}
```

## Authors

- [@lucaslomba](https://github.com/lucaslomba)

