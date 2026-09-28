# Checkpoint 5 - Statistical Computing with R & Python + Machine Learning & Modelling

Projeto acadêmico desenvolvido para o **2º semestre do Tecnólogo em Inteligência Artificial - FIAP**.

O objetivo é integrar **análise estatística de dados** com **modelagem de Machine Learning**, utilizando o dataset **Wines**.

## Integrantes

- Maria Eduarda - Matrícula: PREENCHER
- Giovanna - Matrícula: PREENCHER
- Athur - Matrícula: PREENCHER
- Felipe - Matrícula: PREENCHER

> Observação: as matrículas serão preenchidas antes da entrega final.

## Objetivos do trabalho

### Parte 1 - Statistical Computing with R & Python

Foram selecionadas duas variáveis quantitativas do dataset:

- **Alcohol**
- **Malic.acid**

Para cada variável foram realizadas:

- tabela de distribuição de frequências;
- visualização gráfica;
- medidas de tendência central;
- medidas de dispersão;
- quartis;
- análise probabilística;
- pelo menos dois cálculos de probabilidade;
- interpretações e comentários no código.

### Parte 2 - Machine Learning & Modelling

Foi utilizado o algoritmo **K-means** para agrupar vinhos com características semelhantes.

Etapas realizadas:

- análise inicial do dataset;
- remoção da variável de classe para o processo de clusterização;
- verificação de dados nulos;
- padronização das variáveis;
- treinamento do K-means;
- análise pelo método **Elbow**;
- avaliação com **Silhouette Score**;
- definição do número de clusters;
- comparação das características dos grupos.

## Resultado do agrupamento

A análise indicou o uso de **3 clusters** como uma solução adequada para o conjunto estudado.

Os grupos apresentaram diferenças em características como:

- teor alcoólico;
- ácido málico;
- intensidade de cor;
- Proline;
- demais atributos químicos presentes no dataset.

## Estrutura do repositório

```text
Chekpoint5-SCWR-P/
├── README.md
├── Checkpoint5_Wines.ipynb
├── wine.csv
└── relatorio/
    └── Checkpoint5_Relatorio.pdf
```

## Tecnologias utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook
- K-means
- StandardScaler
- Silhouette Score

## Como executar

1. Clone este repositório.
2. Instale as dependências necessárias.
3. Abra o arquivo `Checkpoint5_Wines.ipynb` no Jupyter Notebook ou VS Code.
4. Execute as células em sequência.

Exemplo de instalação:

```bash
pip install pandas numpy matplotlib scikit-learn jupyter
```

## Entrega acadêmica

O repositório contém o notebook com o código comentado e resultados da análise. O relatório em PDF complementa a entrega do trabalho.

Antes da entrega final, preencher as matrículas dos integrantes tanto neste README quanto no relatório.
