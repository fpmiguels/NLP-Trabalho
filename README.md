# Classificador de Notícias FAKE vs REAL

Este projeto utiliza o corpus Fake.br para treinar um modelo que identifica notícias falsas (FAKE) e verdadeiras (REAL).

Descrição

Corpus: 7.200 notícias (3.600 FAKE, 3.600 REAL).

Pré-processamento: remoção de acentos, conversão para minúsculas, remoção de stopwords, números e pontuação; stemming (RSLP); truncamento para 300 tokens.

Representação: TF-IDF com unigramas, bigramas e trigramas.

Modelo: Regressão Logística balanceada.

Acurácia obtida: 94,72%.

Visualização

Nuvens de palavras para textos FAKE e REAL.

Palavras representadas por frequência e radical.
