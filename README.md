# gqlgen-practice
Golang、GraphQL

### How to run
```
go run server.go
```

### Version
```
go version go1.18.3 darwin/arm64
```

### URL for GraphQL playground
    http://localhost:8080/

    ```
    mutation createTodo {
        createTodo(input: { text: "todo", userId: "1" }) {
            user {
            id
            }
            text
            done
        }
    }
    ```
    
    ```
    query findTodos {
        todos {
            text
            done
            user {
            name
            }
        }
    }
    ```

### Reference
    https://gqlgen.com/getting-started/
