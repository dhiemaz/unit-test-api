# API UNIT TEST
## Golang web api testing samples 

### Run

Build
```
    $ make build
```

Start mongodb container
```
    $ make start
```

Stop mongo container
```
    $ make stop
```

### Tests

Unit tests
```
    $ make test
```

Database integration tests
```
    $ make integration
```

Api acceptance tests
```
    $ make acceptance
```

Test all
```
    $ make test-all
```

### Cover

Generate/update cover
```
    $ make cover
```

view cover html (xdg-open browser default)
```
    $ make cover-html
```

### Requirements

[Docker](https://www.docker.com/)

[Docker compose](https://docs.docker.com/compose/)

[Go 1.10+](https://golang.org/dl/)

[go dep](https://golang.github.io/dep/)
