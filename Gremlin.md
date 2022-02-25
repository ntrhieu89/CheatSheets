#### Record
```
:record start mylog.txt

// execute gremlin queries here

:record stop
```

#### Show all results
```
// Must execute in non-remote mode
result
```

#### Set timeout
```
// Set timeout to 1000 seconds
:remote config timeout 1000000
```

#### Increase the limit when displaying results
```
// To display max 2000 results
:set max-iteration 2000
```

#### Links

* [https://tinkerpop.apache.org/docs/current/reference/#console-preferences]()
