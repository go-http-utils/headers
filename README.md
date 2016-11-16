# headers

HTTP header constants for Gophers.

## Installation

```sh
go get -u github.com/go-http-utils/headers
```

## Documentation

https://godoc.org/github.com/go-http-utils/headers

## Usage

```go
impost (
  "fmt"

  "github.com/DavidCai1993/headers"
)

fmt.Println(headers.HeaderAcceptCharset)
// -> "Accept-Charset"

fmt.Println(headers.HeaderIfNoneMatch)
// -> "If-None-Match"

// ...
```
