# film-junky-union-sentiment-analysis
Projeto de processamento de linguagem natural e machine learning para classificar avaliações de filmes como positivas ou negativas.

## Visão Geral

Este projeto tem como objetivo desenvolver um modelo capaz de classificar avaliações de filmes com base em seu sentimento. A proposta é utilizar técnicas de processamento de linguagem natural e machine learning para identificar se uma review expressa opinião positiva ou negativa.

A análise busca apoiar a **Film Junky Union** na automação da interpretação de feedback textual, transformando grandes volumes de avaliações em informação estruturada e útil para tomada de decisão.

## Problema de Negócio

A **Film Junky Union** precisa analisar avaliações de usuários de forma escalável para entender melhor a recepção dos filmes e o comportamento do público. Como o volume de texto pode ser muito grande, a empresa precisa de uma solução automatizada capaz de classificar sentimentos com boa precisão.

Neste projeto, o desafio é preparar dados textuais, testar modelos e encontrar uma abordagem eficiente para classificação binária de reviews.

## Conjunto de Dados

O conjunto de dados contém avaliações de filmes e seus respectivos rótulos de sentimento, permitindo treinar e avaliar modelos de classificação textual.

Dependendo da versão do projeto, os dados podem incluir informações como:

- texto da avaliação
- polaridade do sentimento
- metadados do filme ou da review
- divisão entre treino e teste

O arquivo utilizado no projeto está organizado na pasta `datasets/`:

- `imdb_reviews.tsv`

## Objetivo do Projeto

Desenvolver uma solução de processamento de linguagem natural e machine learning para classificar avaliações de filmes como positivas ou negativas, com foco em automatizar a interpretação de feedback textual.

## Objetivos da Análise

Este projeto busca responder perguntas como:

- É possível classificar automaticamente avaliações de filmes com boa precisão?
- Quais técnicas de representação textual funcionam melhor no problema?
- Qual modelo apresenta melhor desempenho na classificação de sentimento?
- Como a solução pode ser aplicada em um contexto real de negócio?

## Etapas do Projeto

O projeto foi desenvolvido nas seguintes etapas:

1. carregamento e inspeção inicial dos dados
2. limpeza e preparação dos textos
3. análise exploratória do conjunto
4. vetorização e transformação textual
5. treinamento de modelos de classificação
6. avaliação por métricas apropriadas
7. comparação de resultados
8. conclusões de negócio

## Ferramentas e Bibliotecas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Tqdm
- Jupyter Notebook

## Estrutura do Repositório

```text
film-junky-union-sentiment-analysis/
├── .gitignore
├── README.md
├── requirements.txt
├── film_junky_union_sentiment_analysis.ipynb
└── datasets/
    └── imdb_reviews.tsv
````

## Como executar

1. Clone este repositório:

   ```bash
   git clone https://github.com/IagoZanquetta/film-junky-union-sentiment-analysis.git
   ```

2. Acesse a pasta do projeto:

   ```bash
   cd film-junky-union-sentiment-analysis
   ```

3. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```

4. Abra o arquivo `film-junky-union-sentiment-analysis.ipynb` no Jupyter Notebook, JupyterLab ou VS Code.

5. Execute as células em ordem.

## Principais Pontos Analisados

Entre os principais focos do projeto, estão:

* preparação de dados textuais
* vetorização de reviews
* comparação entre modelos de classificação
* avaliação de desempenho em NLP
* interpretação dos resultados
* aplicabilidade prática para análise de feedback

## Resultados

Demonstração da possibilidade de transformar avaliações textuais em dados estruturados para classificação de sentimento. Preparação do texto, comparação de abordagens de modelagem e avaliação da viabilidade de uma solução automatizada para análise de reviews em grande escala.

O notebook inclui:

* preparação e limpeza dos textos
* exploração inicial dos dados
* transformação textual
* treinamento e avaliação de modelos
* comparação de desempenho
* seleção da melhor abordagem
* conclusões com foco em negócio

## Conclusão

Este projeto demonstra como técnicas de processamento de linguagem natural e machine learning podem ser utilizadas para classificar automaticamente sentimentos em avaliações de filmes. A solução contribui para transformar feedback textual em informação acionável, permitindo análises mais rápidas, escaláveis e consistentes em contextos de negócio.

## O que foi aprendido

Desenvolvimento e consolidação de habilidades em:
- preparação e limpeza de dados textuais
- análise exploratória de bases de reviews
- transformação de texto para modelagem
- avaliação de modelos de classificação
- interpretação de resultados em problemas de NLP

## Melhorias Futuras

Possibilidades de evolução do projeto:
- testar representações textuais mais avançadas
- comparar modelos adicionais de classificação
- incluir técnicas modernas de embeddings
- aprofundar a análise de erros do modelo

## Autor

**Iago Zanquetta**
