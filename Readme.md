git clone https://github.com/Johannes642/chuck-star-wars-app
# Chuck Norris & Star Wars App
## TODO
Update TO 5.0
### .NET CORE 3.1
cd sovtech_chuck-swapi-frontend
### `https://localhost:5001(SSL)`/`http://localhost:5000`
## Frontend
cd sovtech_chuck-swapi-frontend

### `https://localhost:3000`

## API (Open API)

## Swagger
### `https://localhost:5001/swagger/index.html`
```
CHUCK
```
```
SWAPI
```
```
CHUCK & SWAPI SEARCH
```
## CHUCK
### `https://localhost:5001/chuck/categories`
```json
["animal","career","celebrity","dev","explicit","fashion","food","history","money","movie","music","political","religion","science","sport","travel"]
```

### `https://localhost:5001/search?query=vader`
```json
[
    {
        "chuck": {
            "result": [
                {
                    "value": "You can't spell Love without L O, you can't spell is without I S, you can't spell SILO without LOIS. Chuck Norris"
                },
                ...
```
## SWAPI
### `https://localhost:5001/swapi/people`
 - requires bearer token from login
```json 
[
    {
        "swapi": {
            "results": [
                {
                    "name": "Darth Vader"
                },
                ...
]
```
## CHUCK & SWAPI SEARCH

### `https://localhost:5001/search?query=vader`

```json
[
    {
        "chuck": {
            "result": [
                {
                    "value": "In a fight between Batman and Darth Vader, the winner would be Chuck Norris."
                },
                ...
            ]
        },
        "swapi": {
            "results": [
                {
                    "name": "Darth Vader"
                }
            ]
        }
```

By Johannes van der Merwe
