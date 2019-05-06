# README

## Description


```
It will return the books json data (including id, name, created_at, and updated_at).
```

## How to invoke

1. start the server
`rails server -b 0.0.0.0 -p 3000`

2. open the browser to access the following url
`http://localhost:3000/books.json`


## Data Response in JSON format

```ruby
[
  {
    "id": 1,
    "name": "Golang ebook",
    "created_at": "2019-04-28T10:41:44.000Z",
    "updated_at": "2019-04-28T10:41:44.000Z"
  },
  {
    "id": 2,
    "name": "Elixir ebook",
    "created_at": "2019-04-28T10:41:44.000Z",
    "updated_at": "2019-04-28T10:41:44.000Z"
  },
  {
    "id": 3,
    "name": "Rbuy Ebook",
    "created_at": "2019-04-28T10:41:44.000Z",
    "updated_at": "2019-04-28T10:41:44.000Z"
  }
]
```
