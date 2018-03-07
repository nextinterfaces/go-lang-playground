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
    
Then 

    $ cd $GOPATH/src
    $ go install go-lang-playground/hello
    
Which will create hello executable file under `bin`

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
    
