# Projeto K-Nearest Neighbors (KNN)

## Visão Geral do Projeto

Este projeto faz parte do curso de Data Science fornecido pela Ada Tech em parceria com o Santander, sob o programa Santander Coders. O objetivo principal é implementar um algoritmo de aprendizado de máquina usando o método K-Nearest Neighbors (KNN). O algoritmo é projetado para classificar perfis de clientes com base em um conjunto de dados abrangente.

## Algoritmo KNN

K-Nearest Neighbors é um modelo de aprendizado de máquina supervisionado que é simples, interpretável, amplamente conhecido e razoavelmente rápido, tornando-o um excelente benchmark. Pode ser usado tanto para tarefas de classificação quanto de regressão.

### Características
- Simples e fácil de implementar.
- Não requer suposições sobre a distribuição dos dados.
- Adequado para problemas de classificação multiclasse.

### Etapas do Algoritmo
1. **Definir um valor para K (número de vizinhos mais próximos).**
2. **Identificar os K vizinhos mais próximos do ponto a ser classificado usando uma função de distância.**
3. **Para tarefas de classificação: Calcular a moda (etiqueta mais frequente) entre os vizinhos.**
4. **Atribuir o valor/classe ao ponto de interesse com base no cálculo da etapa 3.**

## Definição do Problema

O conjunto de dados consiste em informações de clientes de uma empresa de investimentos. Cada perfil de cliente é rotulado como **Conservador**, **Moderado** ou **Agressivo**, com base em seu portfólio de investimentos. O objetivo é prever esses perfis para novos clientes, a fim de oferecer produtos de investimento adequados.

## Estrutura dos Dados

Os dados seguem o padrão:

[CPF: INT, Perfil do Investidor: STRING, Carteira de Investimento: TUPLA]


## Regras e Restrições
- Criar funções personalizadas, se necessário.
- Módulos externos como numpy e math não são permitidos.
- O projeto foca na implementação de um modelo KNN, a otimização é secundária.
- Normalização das dimensões não é necessária.

## Uso

1. **Carregar o conjunto de dados.**
2. **Pré-processar os dados, se necessário (lidar com valores ausentes, dados categóricos, etc.).**
3. **Implementar o algoritmo KNN seguindo as etapas definidas.**
4. **Testar o algoritmo com dados de amostra para classificar perfis de clientes.**

## Referências e Links Úteis

- [Primeira aparição do modelo KNN](https://apps.dtic.mil/dtic/tr/fulltext/u2/a800276.pdf)
- [Expansão do KNN](http://ssg.mit.edu/cal/abs/2000_spring/np_dens/classification/cover67.pdf)
- Vários casos de uso e artigos de pesquisa
