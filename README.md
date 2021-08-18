# Lab Docker
- [x] Desafio
- [x] Extra

### Dockerfile:
* docker pull orleon/myfirstapp:3.0

ou
* https://hub.docker.com/r/orleon/myfirstapp


### How to: 
Alterar a variável *MSGVAR* no arquivo *vars.env* para exibir o conteúdo desejado.

## Obs:
* Alterei o codigo da *app.py* para usar o primeiro argumento recebido na chamada importando o *sys*: *return html.format(message=os.getenv("MESSAGE", sys.argv[1]), visits=visits)*
* Criei um arquivo de *.env* para receber os conteúdo que será exibido, dessa forma não é necessário alterar o arquivo *docker-compose.yml*
* Imagem está sendo *buildada* a cada update do docker-compose
