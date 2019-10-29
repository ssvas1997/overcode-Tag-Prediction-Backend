# overcode-Tag-Prediction-Backend
Stack Overflow Question Tag Prediction api deployed on heroku

### Endpoint 
- https://overcode-tag-ml-api.herokuapp.com/
- GET Parmeters
  q="<your question>"

### Example request
```
https://overcode-tag-ml-api.herokuapp.com/?q=mysql connection error in php
```
### JSON response
```
{
  "tags": [
    "mysql",
    "php"
  ]
}
```

