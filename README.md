# .Net CI Dojo

Boas vindas ao Dojo de Integração Contínua com .Net

Neste repositório você tem um projeto simples de uma Class Library em .Net com alguns testes escritos.

## O desafio

### Resumo

O desafio deste Dojo é configurar um Pipeline no Gitlab CI que rode o build e os testes do projeto.

O resultado final do desafio deve ser a seguinte imagem:

![resultado](https://i.ibb.co/QmSjPWN/image.png)

### Passo a Passo

1. Fork: Para cumprir o desafio, primeiramente você deve fazer o Fork do projeto para uma conta sua no Gitlab, clicando em "Fork" no canto direito da página principal do repositório:

![Fork](https://i.ibb.co/s5MF55V/image.png)

2. Feito o Fork, na página principal do seu repositório (criado a partir do Fork), você deve clicar em "+ Set up CI/CD", e em seguida em "Configure Pipeline":

![Configure](https://i.ibb.co/rcBrxkQ/image.png)

3. A partir daí começa o desafio de fato. O arquivo `.gitlab-ci.yml` é o que deve conter as configurações necessárias para rodar o seu build e os testes

#### Dica:

A imagem usada por padrão pelo Gitlab não tem o dotnet instalado. Logo, você deve configurar o seu `.gitlab-ci.yml` para usar a imagem `mcr.microsoft.com/dotnet/sdk:latest`.

;)

### Bônus

Caso vocês concluam o desafio, o bônus é configurar o projeto para que métricas de cobertura de testes sejam apuradas automaticamente no Gitlab CI após os testes serem rodados.
