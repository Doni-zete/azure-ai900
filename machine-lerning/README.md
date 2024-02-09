## Machine Learning Automatizado no Azure Machine Learning
Usando um conjunto de dados históricos de aluguel de bicicletas para treinar um modelo. O modelo prevê o número de alugueres de bicicletas esperados num determinado dia, com base em características sazonais e meteorológicas .

**Crie um espaço de trabalho do Azure Machine Learning**
![Criar um workspace](https://github.com/Doni-zete/azure-ai900/blob/main/imgs/create.png)


**Use aprendizado de máquina automatizado para treinar um modelo**

Criando uma nova tarefa de ML automatizado com as seguintes configurações, usando Próximo conforme necessário para progredir através da interface do usuário

![Criar ativo de dados](https://github.com/Doni-zete/azure-ai900/blob/main/imgs/criar%20ativo%20de%20dados.png)



**Implantar e testar o modelo**

No Modelo guia para o melhor modelo treinado pelo seu trabalho automatizado de aprendizado de máquina, selecione Implantar e usar o Serviço web opção para implantar o modelo com as seguintes configurações

![Implantação concluida](https://github.com/Doni-zete/azure-ai900/blob/main/imgs/implanta%C3%A7%C3%A3o%20concluida.png)


**Teste o serviço implantado**

No estúdio Azure Machine Learning, no menu à esquerda, selecione Endpoints e abrir o previsões-rentais ponto final em tempo real.

No previsão-rentais página de ponto de extremidade em tempo real ver o Teste guia.

No Dados de entrada para testar o endpoint painel, substitua o modelo JSON pelos seguintes dados de entrada

![Arquivo json](https://github.com/Doni-zete/azure-ai900/blob/main/imgs/json.png)




[Referência](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html)

