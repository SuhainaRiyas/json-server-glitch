# json-server

## Create your database

1. Clone this repo (https://github.com/SuhainaRiyas/json-server-glitch)
2 . Change the contents of `db.json` to **your own content** according to the [`json-server example`](https://github.com/SuhainaRiyas/json-server-glitch) and then `commit` your changes to git locally.

_this example will create `/users` route , each resource will have `id`, `title` and `content`. `id` will auto increment!_

```json
{
   "users": [
    {
      "name": "Test",
      "email": "test@gmail.com",
      "phone": "9908089066",
      "gender": "Male",
      "languages": {
        "php": false,
        "react": true,
        "angular": true
      },
      "id": 1
    }
  ]
}
```
