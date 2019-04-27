# UCLCoin-2.0
UCLCoin Algoritmo de Consenso 2.0
Este algoritmo irá utilizar o Consenso de Prova de trabalho (Proof of Work- https://pt.wikipedia.org/wiki/Prova_de_trabalho) . 

1º Passo: Realizar um Fork do Git do Orgito (https://github.com/orgito/uclcoin).

2º Passo: Criar o seu próprio servidor (Ex: https://github.com/Hitmasu/uclcoin) 

3º Passo: Hospede a blockchain em um servidor público de sua preferência. (Ex: Azure, AWS ...).

AWS: https://docs.aws.amazon.com/pt_br/elasticbeanstalk/latest/dg/create-deploy-python-flask.html  
AZURE: https://docs.microsoft.com/en-us/azure/app-service/containers/quickstart-python

4º Passo: Cadastre o WebApp no DNS da UCL Coin (https://dnsblockchainucl.azurewebsites.net/) usando sua conta @ucl.br

5º Passo: No campo URL forneça a rota (link do WebApp) para validar o bloco deve ser <seu_servidor>

Considerações:

•	Bloco Gênesis: Todas as contas @ucl.br irão receber 50 UCLCoins quando começar a minerar.

•	A requisição será enviada a todos mineradores (broadcast), os dois primeiros mineradores a responder ganhará a recompensa (1 UCLCoin).

•	Cada transação tem o custo de 2 UCLCoins a serem descontadas do valor da transação.

•	Todos devem ter sua Blockchain sincronizada.





