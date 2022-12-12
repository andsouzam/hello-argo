## Buildar imagem
```
$ docker build -t jeysonlr/argocd:latest .
```

## Subir container da aplicação
``` 
$ docker run --name=argocd --rm -p 8080:8080  jeysonlr/argocd:latest

```