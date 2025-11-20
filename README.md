# SentimentAnalysis_Bitcoin

1. Requisitos:
   - Tener Python 3.10 instalado

2. Instalación:
   - Activar en venv
     bitcoin_env\Scripts\activate
     pip install pandas git+https://github.com/JustAnotherArchivist/snscrape.git

3. Salida:
   - Se genera un archivo CSV con columnas:
     datetime, source, comment, likes, amountComments

Bitcoin.csv : raw data de reddit 
reddt_df.csv : información procesada de reddit
x_df : información procesada de X
