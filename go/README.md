# Desafio
- Usar uma função chamada "greeting" que recebe a string "Code.education Rocks!" como parametro.
- Rodar na porta 8000
- Exibir "Code.education Rocks!" (em negrito).

### Como rodar os testes:
- Dentro do diretório `./src`
```shell script
$ go test main.go main_test.go
```

### Como rodar o container:
```shell script
$ docker run --rm --publish 8000:8000 vlademirdocker/k8s-gcp-go
```

# Extras:
- [Go Lint Pipeline](https://github.com/golangci/golangci-lint)
- [Go Sec Pipeline](https://rollout.io/blog/put-gosec-pipeline-spot-source-code-security-problems/)