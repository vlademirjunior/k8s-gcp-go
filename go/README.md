# Desafio de CI

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