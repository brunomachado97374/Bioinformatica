# Bioinformatica

## Trabalho Prático - Opção B2 - BBB (Blood-Brain Barrier)

### Descrição do Dataset

A barreira hemato-encefálica (BBB) representa um componente essencial e complexo do sistema nervoso central, exercendo uma função vital ao separar o sangue circulante do fluido extracelular cerebral. Esta barreira desempenha um papel fundamental na proteção do cérebro, controlando quais substâncias podem entrar ou sair. Uma de suas principais funções é bloquear a maioria dos fármacos estranhos, limitando sua passagem para o tecido cerebral.

O desafio intrínseco a si associado reside na capacidade seletiva de permitir a entrada de nutrientes essenciais enquanto restringe substâncias prejudiciais. No entanto, essa seletividade também cria um obstáculo significativo no desenvolvimento de fármacos destinados ao tratamento de distúrbios do sistema nervoso central. A capacidade limitada de muitos medicamentos atravessarem a mesma impõe restrições consideráveis à eficácia dos tratamentos disponíveis.

Neste estudo, iremos explorar um conjunto de dados de compostos farmacêuticos. Estes são descritos pela sua fórmula molecular, bem como a sua capacidade de penetrar a barreira hemato-encefálica. Ao analisar múltiplos fármacos, pretendemos obter uma compreensão mais abrangente das interações entre estrutura química e resposta biológica, contribuindo assim para o desenvolvimento de conhecimentos mais robustos.

Desta forma, o foco deste estudo passa por analisar diversos fármacos, percebendo a relação entre suas estruturas moleculares e a sua capacidade de penetrar a BBB.

### Informações do Dataset

Dataset: BBB (Blood-Brain Barrier), Martins et al.

Linhas: 1976

Colunas: Drug_ID, Drug, Y

Input: Drug (SMILES)

Objetivo: Prever a penetração da barreira hemato-encefálica pelos vários fármacos existentes no dataset.

Link: https://tdcommons.ai/single_pred_tasks/adme/#bbb-blood-brain-barrier-martins-et-al

### Metodologia de Trabalho (Notebook)

#### Secção 1 - Exploração do Dataset e Análise de Dados 

Carregamento de dados para análise e adição ao dataset de vários descritores relacionados com o SMILES referentes a cada fármaco, obtendo assim um conjunto de dados com variáveis numéricas. Descrição de dataset e caracterização de dados atribuídos com base em literatura disponibilizada. Vizualição de gráficos exploratórios de caracterísitcas principais dos dados. Etapas de tratamento de dados, nomeadamente tratamento de valores nulos e remoção de valores duplicados. 

#### Secção 2 - Redução de Dimensionalidade

Normalização e filtração de dados, bem como utilização de métodos de redução de dimensionalidade com o objetivo de encontrar o menor conjunto de variáveis capazes de descrever a máxima variabilidade dos dados, diminuindo a quantidade de dados a serem avaliados.

#### Secção 3 - Modelos de Aprendizagem

Desenvolvimento e aplicação de algoritmos de aprendizagem máquina supervisionada (Logistic Regression, Decision Tree, Random Forest, Naive Bayes e SVC). Análise de comportamento de modelos baseada em métricas de erro (accuracy, precision, recall e f1-score) e aplicação de métodos de particição de dados (Split Data e Cross-Validation). Desenvolvimento e avaliação de Ensemble Model. Análise e interpretaçao de resultados.

### Literatura:

https://pubmed.ncbi.nlm.nih.gov/22612593/

Introduction to the Blood-Brain Barrier: Methodology, biology and pathology; Pardridge, W. M., Ed.; Cambridge University Press: 1998.

Kortagere, S.; Chekmarev, D.; Welsh, W.; Ekins, S. New Predictive Models for Blood-Brain Barrier Permeability of Drug-like Molecules. Pharm. Res. 2008

### Grupo 2

#### Trabalho elaborado por:

Beatriz Rodrigues, PG53696

Bruno Machado, PG53709

Diogo Moura, PG53782


