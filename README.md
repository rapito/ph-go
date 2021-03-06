# ph-go

[![GoDoc](https://godoc.org/github.com/rapito/ph-go/printhouse?status.svg)](https://godoc.org/github.com/rapito/ph-go/printhouse)

The GO API client for printhouse.io

## Installation
```
    go get github.com/parnurzeal/gorequest
    go get github.com/bmizerany/assert
    go get github.com/bitly/go-simplejson
    go get github.com/avelino/awesome-go
    go get github.com/printhouse/ph-go
```

## How-to-use

- Get Requests

```
    import "fmt"
    import "github.com/rapito/ph-go/printhouse"
    ...

    ph := printhouse.New(clientID,clientSecret)
    products, _ := ph.GetProducts()

    fmt.Printf("Retrieved %v products",len(products))
```

- Check out the *examples* folder for simple usage.
- Read some of the tests at *ph_test.go* for more examples.

## Documentation

- Read the Endpoints.md file on the project root.
- To see which endpoints you have access to, check out printhouse web-api [documentation.](http://www.printhouse.io/faqs/)

## Dependencies

This project was created using these awesome libraries, check them out:

 - http://github.com/parnurzeal/gorequest
 - http://github.com/franela/assert
 - http://github.com/bitly/go-simplejson
 - http://github.com/avelino/awesome-go




