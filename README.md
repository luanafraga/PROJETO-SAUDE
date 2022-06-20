# PROJETO-SAUDE

**Previsão de diabetes, batimentos cardíacos e nível de colesterol dos pacientes**

O projeto foi desenvolvido utilizando linguagem **Python** no Jupyter Notebook. O python possui um série de bibliotecas que nos auxiliam na construção das análises e modelagem dos dados. Neste projeto, foram utilizadas as seguintes:

   - Pandas
   - Numpy
   - Seaborn
   - Matplotlib
   - Plotly
   - Scikit-learn

**Objetivo**

O objetivo deste projeto é criar modelos para previsão de:
   
   - **Teste Positivo ou Negativo para Diabetes** de acordo com a Idade, IMC, Concentração de Glicose etc ;
    
   - **Batimentos Cardíacos** de acordo com o Peso e Horas de atividade física ;
   
   - **Nível de Colesterol** de acordo com a Idade, Gênero, Tipo de dor no peito, etc.

**Dados**

A base de dados possui informações sobre:

   - **Diabetes**:
        - quantidade gravidez
        - concentração glicose
        - pressão
        - espessura tríceps
        - insulina
        - imc
        - diabetes pedigree
        - idade
        - resultado
        
   - **Batimentos cardíacos**:
        - idade
        - peso
        - horas de atividade
        - batimentos cardíacos
       
   - **Colesterol**:
        - idade
        - gênero
        - tipo dor peito
        - pressão sanguínea repouso
        - açúcar jejum
        - resultado eletrocardio
        - freq cardio max
        - angina exercicio
        - depressão induzida exercicio
        - inclinação
        - num princ vasos
        - thal
        - diag doenca cardiaca
        - colesterol


**Conclusões**


Após o pré-processamento dos dados, foi criado para o dataset **Diabetes** o modelo de **classificação Árvore de Decisão**, para o dataset **Batimentos cardíacos** o modelo de **Regressão Logística** e para o dataset **Colesterol** o modelo de **Clusterização KMeans** . Esses modelos foram treinados e avaliados utilizando métricas de avaliação matemáticas e gráficas.
