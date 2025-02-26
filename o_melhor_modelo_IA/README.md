# Descrição
Neste desafio, o objetivo ajudar na escolha do modelo de inteligência artificial mais adequado com base em critérios específicos definidos pelo cliente, utilizando as inovações recentemente anunciadas pela Amazon Web Services (AWS). Os modelos de IA disponíveis são da família Claude 3, desenvolvidos pela Anthropic, que foram anunciados como disponíveis na plataforma Amazon Bedrock. Esses modelos de última geração foram projetados para oferecer um equilíbrio entre precisão, desempenho, velocidade e custo, atendendo às demandas de clientes de todos os tamanhos.

Atenção:
Alguns dados que utilizados são simulados e podem não representar situações reais.

## Entrada
A entrada consiste em quatro linhas, cada uma representando uma característica do modelo de inteligência artificial:

1. Desempenho: um número inteiro indicando a capacidade de desempenho do modelo.
2. Velocidade: um número inteiro representando a velocidade de processamento do modelo.
3. Custo: um número inteiro que reflete o custo associado ao modelo.
4. Capacidades: uma lista de capacidades específicas separadas por vírgulas.

## Saída
O programa fornecerá a recomendação do modelo mais adequado com base nas características fornecidas. A saída incluirá uma explicação detalhada sobre por que esse modelo específico foi escolhido com base nos critérios estabelecidos pelo cliente, utilizando informações sobre os modelos Claude 3 disponíveis na plataforma Amazon Bedrock. Se nenhum modelo atender aos critérios, o programa informará que nenhum modelo foi encontrado.

## Exemplos
A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis.


| Entrada                       | Saída                             |
|-------------------------------|-----------------------------------|
| 9 10 5 Pesquisa, Desenvolvimento Acelerado | O Claude 3 Opus é o modelo recomendado. |
| 8 5 7 Codificação, Recuperação de informações | O Claude 3 Sonnet é o modelo recomendado. |
| 7 9 6 Velocidade, Resumo de dados não estruturados | O Claude 3 Haiku é o modelo recomendado. |
| 1 5 9 Viagem interplanetária, Autoconhecimento | Nenhum modelo encontrado |
