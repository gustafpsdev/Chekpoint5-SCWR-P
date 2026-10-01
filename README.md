# Checkpoint 5 - Statistical Computing with R & Python + Machine Learning & Modelling

Projeto acadêmico do 2º semestre do Tecnólogo em Inteligência Artificial - FIAP.

## Integrantes
- Maria Eduarda - Matrícula: PREENCHER
- Giovanna - Matrícula: PREENCHER
- Athur - Matrícula: PREENCHER
- Felipe - Matrícula: PREENCHER

## Objetivo
Integrar análise estatística descritiva/probabilística com modelagem não supervisionada usando o dataset Wines.

## Parte 1 - Statistical Computing with R & Python
Variáveis analisadas: `Alcohol` e `Malic.acid`.

Inclui:
- tabelas de distribuição de frequências e histogramas;
- média, mediana, moda, amplitude, variância, desvio padrão e coeficiente de variação;
- quartis e IQR;
- dois cálculos probabilísticos para cada variável;
- comparação entre aproximação Normal e frequência empírica;
- interpretações dos resultados.

## Parte 2 - Machine Learning & Modelling
Inclui:
- remoção da feature de classe `Wine`;
- verificação de nulos;
- padronização com `StandardScaler`;
- ajuste do K-means;
- Elbow Method;
- Silhouette Score;
- escolha de `k = 3`;
- análise e visualização dos perfis dos clusters.

O melhor Silhouette Score entre `k = 2` e `k = 8` ocorre em `k = 3` (aprox. 0,2849).

## Estrutura
```text
Chekpoint5-SCWR-P/
├── README.md
├── Checkpoint5_Wines.ipynb
├── wine.csv
├── requirements.txt
└── relatorio/
    └── Checkpoint5_Relatorio.pdf
```

## Como executar
```bash
pip install -r requirements.txt
jupyter notebook Checkpoint5_Wines.ipynb
```

O notebook está salvo com as células executadas e resultados/gráficos incorporados.

## Entrega
No Microsoft Teams, enviar o PDF com nomes e matrículas e o link deste repositório GitHub com o notebook executado e comentado.