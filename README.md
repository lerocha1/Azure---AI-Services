
# DIO - Azure Machine Learning

Este projeto visa facilitar o uso do ml.azure.com na prática. Mostrando uma analise de dados de alugueis de bicileta utilizando Regressão Linear como exemplo.




## Como chegar lá?

Acesse o [Azure](https://azure.com) e logue com sua conta. CAso não tenha crie uma gratuita.

* Caso precise criar uma conta gratuita, será necessário informar um cartão de credito válido. A microsoft libera um credito para você usar dentro do azure, mas fica com um cartão caso haja excessos.

* Assim que acessar pela primeira vez, você será obrigado a criar uma área de trabalho, ou um workspace.

![](/imagens/logo_mlazure.png)


Workspace criado, vamos selecionar ML Automatizado, que fica a esquerda da sua tela. e na squencia novo Trabalho.

Prencha os dados que se pede mas nao precisa criar nenhum marcador.

Crie uma base de dados nova. Preencha nome e descrição. O pulo está Tipo do tipo, selecione Tabular.
base de dados utilizada [bike_rental](https://aka.ms/bike-rentals). Aqui usar arquivos da web.


Por utimo, usar os pontos de Endpoints para o modelo se orientar e criar um predict de aluguel de bicicletas.

 {
   "Inputs": { 
     "data": [
       {
         "day": 1,
         "mnth": 1,   
         "year": 2022,
         "season": 2,
         "holiday": 0,
         "weekday": 1,
         "workingday": 1,
         "weathersit": 2, 
         "temp": 0.3, 
         "atemp": 0.3,
         "hum": 0.3,
         "windspeed": 0.3 
       }
     ]    
   },   
   "GlobalParameters": 1.0
 }


## Referência

 - [Documentação Azure](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html)
 - [Portal Azure](https://portal.azure.com)
 - [Base de dados](https://aka.ms/bike-rentals)


## Autores

- [@lerocha1](https://www.github.com/lerocha1)


## 🚀 Sobre mim
Pai, ciclista e apaixonado por Tecnologia, atuo como Gerente multidisciplinar em uma empresa de engenharia e que nas horas vagas "gasto" meu tempo com programação e desafios na internet.

Programando marjoritariamente em Python, também especialista em banco de Dados, Analise de dados/Big Data e programador FullStack.
