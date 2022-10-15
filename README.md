# FerramentafakenewsR
Ferramenta para Verificação de Notícias Falsas
{ projeto em construção}
***última atualização : 14 de outubro de 2022.

# Sobre os Dados e API
Nessa Ferramenta em construção, foi usado o modelo de API presente no : https://github.com/fake-news-api/fake_news_detection_api(Diretório de Vu Luong)
Foram adequados os dados necessários e  a inclusão de um corpus autoral com :
TRUE    1110
FAKE    1040

Diretório do corpus: 

  precision    recall  f1-score   support

        FAKE       0.80      0.88      0.84       485
        TRUE       0.89      0.82      0.86       590

    accuracy                           0.85      1075
   macro avg       0.85      0.85      0.85      1075
weighted avg       0.85      0.85      0.85      1075


Fontes : 
Noticias Fontes que utilizei: CNN, G1, BBC, Daily News, Foreign Affair, Twitter**, Metrópoles, R7, AFP, Aos Fatos, E-Farsas, Fake.Br(Corpus Prof Tiago Pardo e Roney Lira USP).

Objetivo Detecção Automática de Fake News

Maiorias das noticias são de 2020-2022 com foco em pandemia, guerra e eleições.

Politica Internacional
Politica
Sarcasmo( - sendo testado em corpus próprio)
Saúde
Justiça
Economia
Entretenimento
Palavras Chaves dos temas relacionados: Covid, Covid-19, Pandemia , Guerra, Ucrânia, Rússia, Eleições 2022, Vacina, Variola, Meio Ambiente.

 Api no Heroku:

