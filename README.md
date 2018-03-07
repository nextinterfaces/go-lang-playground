# go-lang-playground

Go-lang kitchen sink app collection

#### Go Commands


Assume $GOPATH workspace structure is:
    
    |
    +- bin
    |
    +- pkg
    | 
    +- src
         |
         +- go-lang-playground
    
Create dependencies to `pkg` 

    $ cd $GOPATH/src
    $ go build go-lang-playground/stringutil
    $ go install go-lang-playground/stringutil
    
Create executables to `bin` 
    
    $ go install go-lang-playground/hello


Run executables
 
    $ hello

Alternatively 

    $ go build hello/hello.go
    $ ./hello
    $
    $ go build web/webserver.go
    $ ./webserver
    $
    $ go build web/webserver_content.go
    $ ./webserver_content
    
