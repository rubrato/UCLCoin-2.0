# UCLCoin-2.0
UCLCoin Algoritmo de Consenso 2.0

1º Passo: Realizar um Fork do Git do Orgito (https://github.com/orgito/uclcoin).

2º Passo: Criar o seu próprio servidor (Ex: https://github.com/Hitmasu/uclcoin) 

3º Passo: Hospede a blockchain em um servidor público de sua preferência. (Ex: Azure, AWS ...).

AWS: https://docs.aws.amazon.com/pt_br/elasticbeanstalk/latest/dg/create-deploy-python-flask.html  
AZURE: https://docs.microsoft.com/en-us/azure/app-service/containers/quickstart-python

4º Passo: Cadastre o WebApp no DNS da UCL Coin (https://dnsblockchainucl.azurewebsites.net/) usando sua conta @ucl.br

5º Passo: No campo URL forneça a rota (link do WebApp) para validar o bloco deve ser <seu_servidor>

Atenção: Seu servidor deve conter a rota /block.
