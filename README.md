# Go gRPC Server
Uma implementação de um servidor gRPC em Go.
Baseado no curso [Go Experts](https://goexpert.fullcycle.com.br/curso/).
## Comando de Geração
    
```
protoc --go_out=. --go-grpc_out=. proto/course_category.proto
```
## Comando para Criar o banco de dados

```
sqlite3 db.sqlite < db.sql
```

## Comando para rodar o servidor

```
go run cmd/server/main.go
```
   

## Comando para instalção do Evans

```
go get github.com/ktr0731/evans@latest
```
## Comando para rodar o cliente

```
evans -r repl -p 50051
```
>
 > package pb

 > service CategoryService

 > call CreateRequest

 > call UpdateRequest

 > call DeleteRequest

 > call GetRequest

 > call GetAllRequest
