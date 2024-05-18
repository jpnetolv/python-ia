# Previsão de Score de Crédito

## Descrição

Este projeto demonstra como construir e implementar um modelo de machine learning para prever scores de crédito utilizando dados de clientes. O processo envolve a preparação dos dados, o treinamento e teste de dois algoritmos de machine learning, e a utilização do modelo de melhor desempenho para prever scores de crédito de novos clientes.

## Estrutura do Projeto

O projeto está organizado da seguinte forma:

```
/previsao-score-credito
│
├── dados/
│   ├── clientes.csv
│   └── novos_clientes.csv
│
├── src/
│   ├── preprocessamento.py
│   ├── treinamento.py
│   └── predicao.py
│
├── README.md
└── requirements.txt
```

### dados/clientes.csv

Este arquivo contém os dados dos clientes, incluindo atributos como profissão, mix de crédito, comportamento de pagamento e score de crédito. Esses dados são utilizados para treinar e testar os modelos de machine learning.

### dados/novos_clientes.csv

Este arquivo contém os dados de novos clientes para os quais os scores de crédito serão previstos utilizando o modelo treinado.

### src/preprocessamento.py

Este arquivo contém as funções para carregar os dados, realizar a codificação dos atributos categóricos e dividir os dados em conjuntos de treino e teste.

### src/treinamento.py

Este arquivo contém a lógica para treinar os modelos de machine learning (Random Forest e K-Nearest Neighbors), avaliar seu desempenho e selecionar o melhor modelo.

### src/predicao.py

Este arquivo contém a lógica para utilizar o modelo treinado para prever os scores de crédito dos novos clientes.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests para adicionar novas funcionalidades, corrigir bugs ou melhorar o projeto.

## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).