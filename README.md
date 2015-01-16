logger 
=======

A tiny middleware for negroni et al. Writes logs in json which makes it easy to get them into elasticsearch.

### Go get it

```
go get github.com/sontags/logger
```

### Usage

Easy:

```
// ...
func main() {}
    // ...
	n := negroni.New(
		negroni.NewRecovery(),
		logger.NewLogger(),
	)
	// ...
}
```
