# **Projeto- Case Airbnb**
Análise exploratória dos dados da empresa de hospedagem Airbnb, identificando os principais insights sobre o mercado de aluguel de imóveis por temporada.

Escola: SoulCode Academy

Curso: Bootcamp Analista de Dados - Martech - AD2

Período: Semana 6 - ETL

Professor: Franciane Rodrigues

Professor: Jonathas Carneiro

Aluno: Renato Gonçalves Costa

### **Como visualizar o projeto**

Para visualizar o projeto, você não precisa necessariamente executar o código. O projeto está no modo de exibição. Isso significa que qualquer pessoa que tenha o link para o notebook poderá visualizá-lo, inclusive os resultados, as análises e os gráficos. Para abrir o notebook Colab do projeto de análise de dados do Airbnb no GitHub, siga estas etapas:
Acesse o repositório do projeto no GitHub.
Clique na pasta de nome "notebook_colab", em seguida clique no arquivo "Semana_6_Projeto_03_Case_Airbn_aluno_renato_costa_AD2.ipynb",  ao clicar no arquivo clique no icone Abrir no Colab, localizado no canto superior esquerdo da página.

### **Execução do Projeto**

Para executar o projeto de análise de dados do Airbnb, é necessário fazer upload do arquivo airbnb.csv. O arquivo está disponível para download na pasta "datasets" do projeto Airbnb no GitHub.

Para fazer upload do arquivo airbnb.csv para o Google Colab, siga estas etapas:
Abra o notebook Colab.
Na barra lateral esquerda, clique em "Arquivos".
Na seção "Upload", clique em "Escolher arquivo".
Selecione o arquivo airbnb.csv que você deseja fazer upload.
Clique em "Abrir".

Para rodar o projeto, siga estas etapas:
Clique na célula de código que você deseja executar.
Pressione Shift + Enter para executar a célula.
Assim que todas as células forem executadas, você poderá visualizar os resultados das análises de dados.

### **O que é Airbnb**?
O Airbnb é uma plataforma online que permite que pessoas ofereçam e reservem acomodações em todo o mundo. É uma forma alternativa de hospedagem, onde os anfitriões disponibilizam seus espaços, como quartos, apartamentos, casas ou até mesmo castelos, para serem alugados por curto ou longo prazo.

### **Informações gerais da base de dados**
Claro, aqui está o texto atualizado com a adição de que os datasets são arquivos CSV:

Este conjunto de dados contém informações sobre aluguéis de Airbnb em cidades europeias, incluindo características e seus efeitos sobre o preço. Os datasets fornecidos são em formato CSV e incluem várias informações, como o preço total do anúncio, tipo de quarto, status do anfitrião (superhost ou não), comodidades e informações de localização.
Fonte: https://www.kaggle.com/datasets/thedevastator/airbnb-price-determinants-in-europe

### **Pergunta de negócio**
 Fazer uma análise exploratória de dados com a base de dados do Airbnb e indicar possíveis oportunidades e/ou ameaças para o empreendimento.

 ### **Dicionário sobre a base de dados Airbnb**

*   realSum: preço total da acomodação para duas pessoas e duas noites em EUR;  
*   room_type: tipo de quarto oferecido;
*   room_shared: se o quarto é compartilhado ou não;
*   room_private: se o quarto é privativo ou não;
*   person_capacity: número máximo de pessoas permitidas na propriedade;
*   host_is_superhost: se o host é ou não um superhost;
*   multi: tem vários quartos ou não;
*   biz: seja para uso comercial ou familiar;
*   cleanliness_rating: Classificação de limpeza (escala de pontuação:0-10);
*   guest_satisfaction_overall: satisfação geral do hóspede (escala pontuação: 0-100);
*   bedrooms: número de quartos;
*   dist: a distância do centro da cidade;
*   metro_dist: a distância da estação de metrô mais próxima;
*   metro_dist: distância da estação de metro mais próxima em km;
*   attr_index: índice de atração do local do anúncio;
*   attr_index_norm: índice de atracção normalizado ( escala de pontuação: 0-100);
*   rest_index:índice de restaurantes do local do anúncio;
*   rest_index_norm: índice de restaurantes normalizado (escala de pontuação: 0-100);
*   lng: Longitude
*   lat: Latitude
 
### **Tecnologias utilizadas**
   * Python (Linguagem de programação)
   * Pandas (truturas de dados e operações para manipular tabelas numéricas e séries temporais)
   * Google Colab (ambiente de programação interativo que permite escrever e executar código do Python  e suas bibliotecas no navegador)
   * Google Cloud (serviço de armazenamento em nuvem)
   * Numpy (biblioteca popular em Python para computação numérica e manipulação de dados)
   * Matplotlib (biblioteca em Python utilizada para criação de gráficos e visualizações de dados)
   * Panderas (uma biblioteca que adiciona recursos de validação de dados)
   * OS (interagir com o sistema operacional)

### **Nível - Tratamento**

  *   Verificar todos os passos da estratégia de análise geral de análise de dados;
  *   Executar os procedimentos necessários para realizar o ETL;
  *   Todos os passos de ETL deverão ser comentados;
  
    
### **Pré-Análise**
Essa etapa de **pré-análise** preliminar possibilita identificar problemas, como valores ausentes, inconsistências ou dados duplicados, e aplicar as devidas correções, garantindo a confiabilidade e integridade dos dados. Além disso, a pré-análise auxilia na escolha adequada das variáveis relevantes para a análise.

*   Visualização dos dados;
*   Avaliação das possibilidades do que faremos;
*   Transformação o Escolher as possíveis colunas importantes para a análise;
*   Verificar se há colunas iguais;
*   Verificação e tratamento de duplicadas;
*   Verificação e tratamento de valores nulos;
*   Verificação e tratamento de valores únicos;
*   Verificação e tratamento de inconsistência;
*   Renomeação das colunas ( se caso for necessário);
*   Transformação de tipos de dados adequados;

### **Transformação**
**Após escolher as colunas ( atributos) importantes para a análise, o objetivo nesta etapa é garantir a qualidade e a integridade dos dados do DataFrame. Fazer as verificações ajuda a indentificar e tratar problemas que podem comprometer futuras análises e tomadas de decisão. A seguir temos os tópicos de verificação:

*  Verificar se há colunas iguais;
*  Verificação e tratamento de valores (ou observações) únicos;
*  Verificação e tratamento de duplicadas
*  Verificação e tratamento de inconsistência
*  Verificação e tratamento de valores nulos
*  Tradução/Renomeação
*  Transformação de tipos adequados dos dados
*  Garantia de qualidade e integridade dos dados
  
### **Análise**
*   Realizar  análises  numéricas;
*   Realizar plotagens (gráficos) das análises;
*   Chegar a uma conclusão sobre a análise Airbnb;

### **Visualização (Gráficos)**
 *   Os tipos gráficos utilizados neste projeto foram: Gráfico de Barras, Gráfico de Dispersão, Gráfico de  Histograma e Boxplot


### **Insights**

Contagem de Tipo de Quarto e Preço Médio: Com base na análise gráfica da contagem de cada tipo de quarto, observou-se que os tipos de quartos mais populares são "Entire home/apt" e "Private room". Além disso, o preço médio mais alto é associado ao tipo "Entire home/apt" (R$ 914.09), indicando uma demanda considerável por acomodações completas e bem localizadas.

Medidas Estatísticas do Preço Total: Os insights obtidos a partir do gráfico de barras das medidas estatísticas do preço total incluem:

Preço Competitivo: Quando o preço total está abaixo da média ou no quartil inferior (25%), pode indicar uma boa relação custo-benefício, atraindo mais clientes.
Oportunidades de Aumento de Preço: Se o preço total estiver abaixo da média, o proprietário pode considerar aumentá-lo, desde que a qualidade e os serviços oferecidos justifiquem o aumento.
Relação entre Preço Total e Satisfação Geral do Hóspede: Existe uma tendência positiva entre o preço total da hospedagem e a satisfação geral dos hóspedes. Os hóspedes estão dispostos a pagar mais por uma experiência que os satisfaça em diversos aspectos.

Preço Total: A mediana do preço total está em torno de 768,16. O primeiro quartil indica que 25% das hospedagens têm preços abaixo de 628,50, enquanto o terceiro quartil mostra que 75% das hospedagens têm preços abaixo de 996,65.
Distância ao Centro: A mediana da distância ao centro é de cerca de 2,525 km. O primeiro quartil indica que 25% das hospedagens estão a uma distância de 1,718 km ou menos do centro, enquanto o terceiro quartil mostra que 75% das hospedagens estão a uma distância de 3,737 km ou menos do centro.
Distância ao Metrô: A mediana da distância ao metrô é de aproximadamente 1,16 km. O primeiro quartil indica que 25% das hospedagens estão a uma distância de 0,69 km ou menos do metrô, e o terceiro quartil mostra que 75% das hospedagens estão a uma distância de 1,86 km ou menos do metrô.
Índice de Atrações: A mediana do índice de atrações é de cerca de 195,85. O primeiro quartil indica que 25% das hospedagens têm um índice de atrações de 112,21 ou menos, enquanto o terceiro quartil mostra que 75% das hospedagens têm um índice de atrações de 327,69 ou menos.

### **Considerações**

Para proprietários de hospedagens, os insights fornecem informações valiosas para ajustar preços, considerar estratégias de marketing e melhorar a experiência do hóspede.
Investir em melhorias na qualidade do serviço, com foco em limpeza, comodidades e atendimento ao cliente, é essencial para justificar preços mais altos e garantir a satisfação dos hóspedes.
Segmentar estratégias de preços com base na localização, proximidade ao centro e ao metrô é uma abordagem eficaz para atrair diferentes tipos de hóspedes.
Proprietários de hospedagens do tipo "Entire home/apt" podem se destacar com base nas comodidades oferecidas, na privacidade e na excelente localização.
Potenciais investidores podem considerar o segmento de "Entire home/apt" como uma oportunidade lucrativa no setor de hospedagem do Airbnb.


### **Documentação:**

      * Python: link: https://docs.python.org/3/
      * Pandas: link: https://pandas.pydata.org/docs/
      * Numpy: link: https://numpy.org/doc/
      * Matplotlib: link: https://matplotlib.org/
      * Pandera: link: https://pandera.readthedocs.io/en/stable/
      * Airbnb link: https://www.airbnb.com/     
      * Base de dados Airbnb: Link: https://www.kaggle.com/datasets/thedevastator/airbnb-price-determinants-in-europe
      * Determinants of Airbnb prices in European cities: A spatial econometrics approach. Link: https://www.sciencedirect.com/science/article/pii/S0261517721000388?via%3Dihub
      * MapQuest Geocode reverso: Link: https://developer.mapquest.com/documentation/geocoding-api/reverse/get/
