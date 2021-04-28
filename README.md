# fullcycle-docker-desafio1
Desafio do curso FullCycle 2.0 - Docker usando Go.

### Descrição do desafio
> Gerar uma imagem usando Golang que quando acessada, gerar uma mensagem para usuário final "Full Cycle Rocks !!!". A cereja do bolo é q a imagem resultante não pode ultrapassar 2Mb

__O retorno da aplicação go deverá ser:__
uma mensagem para usuário final "Full Cycle Rocks !!!"

### Requisitos
1. A imagem resultante não pode ultrapassar 2Mb

  
### Para rodar :zap:
```
git clone https://github.com/dennysvf/fullcycle-docker-desafio1.git

cd fullcycle-docker-desafio1/go

docker build -t autotrend/fullcycle-docker-desafio1 .

docker run autotrend/fullcycle-docker-desafio1


```

### Para rodar  direto do Hub.Docker :zap:


```
docker run autotrend/fullcycle-docker-desafio1
```

<br/>
<br/>