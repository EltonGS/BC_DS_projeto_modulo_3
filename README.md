<p align="center">
  <img alt="Análise dos casos e óbitos de Covid-19 em Santo André - SP e criação de modelo de previsão com Facebook Prophet" src="https://github.com/EltonGS/BC_DS_projeto_modulo_3/blob/main/imagens/covid-19_0.jpg" />
  
# Introdução 

Este é o terceiro projeto do **Bootcamp de Data Science Aplicada** que está sendo ministrado pela **Alura Cursos**.
O **objetivo** desse projeto é **trabalhar com uma série temporal** e criar um **modelo de previsão com a biblioteca Facebook Prophet**.

Os dados foram obtidos através do site [Brasil.IO](https://brasil.io/dataset/covid19/caso_full/). A planilha analisada é a **caso_full**.
O **Brasil.IO** é uma força tarefa de 40 voluntários criada para fornecer **bases de dados** com a série histórica dos **casos e óbitos de Covid-19** por município. **O objetivo é facilitar o acesso a dados já padronizados**.

**Os dados analisados nesse projeto foram obtidos na data 28/06/2021**.

O **município** escolhido para o projeto é **Santo André**, localizado no estado de São Paulo. **Por coincidência esse é o município onde vivo**.

# Objetivo
  
O **objetivo** do projeto é **trabalhar com uma série temporal** e criar um **modelo de previsão da série temporal** utilizando a biblioteca **Facebook Prophet**.
  
# Linha do Tempo da pandemia de Covid-19 em Santo André - SP
  
- Primeiro caso identificado em 17 de Março de 2020. Fonte: [O Globo](https://oglobo.globo.com/sociedade/santo-andre-no-abc-paulistaconfirma-primeiro-caso-de-coronavirus-24309496).
- Primeiro óbito ocorreu em 25 de Março de 2020. Fonte: [Diário do Grande ABC](https://www.dgabc.com.br/Noticia/3359925/santo-andre-registra-primeiro-obito-pelo-novo-coronavirus).
- Fechamento do coméricio ocorreu entre 23 de Março e 11 de Abril de 2020. Fonte: [Prefeitura de Santo André](https://www3.santoandre.sp.gov.br/coronavirus/?page_id=90#:~:text=Altera%20o%20Decreto%20n%C2%BA%2017.328,da%20pandemia%20decorrente%20do%20Coronav%C3%ADrus.).
- Outro ações foram tomadas, como adiantamento de feriados, na tentativa de diminuir o número de contaminação. Fonte: [Diário do Transporte](https://diariodotransporte.com.br/2020/05/19/quatro-cidades-do-abc-paulista-decretam-antecipacao-do-feriado-de-corpus-christi-e-tres-aguardam-aprovacao-do-legislativo/).
- A vacinação iniciou na cidade no dia 19 de Janeiro de 2021. Fonte: [Fundação do ABC](https://fuabc.org.br/noticias/santo-andre-chega-a-marca-de-100-mil-vacinados-contra-covid-19-no-aniversario-da-cidade/).
- Santo Andre registra até o momento - 04/07/2021:
  - Casos confirmados: **61.267**
  - Óbitos confirmados: **2324**
  - Vacinados com 1ª dose: **351.434**
  - Vacinados com 2ª dose: **110.480**
  
# Tecnologias utilizadas no projeto
  
Esse projeto foi realizado utilizando o [Google Colab](https://colab.research.google.com/) e as seguintes tecnologias e bibliotecas:
  - Linguagem de Progração Python versão 3.8.5
  - Biblioteca Pandas versão 1.1.5 - Utilizada para manipulação dos dados
  - Biblioteca Matplotlib 3.2.2 - Utilizada para visualização dos dados em gráficos
  - Biblioteca Seaborn versão 0.11.1 - Utilizada para visualiação dos dados em gráficos
  - Facebook Prophet versão 0.7.1 - Utilizada para realizar previsão em séries temporais
  
# Divisão do Projeto
  
O projeto está divido nos seguintes notebooks:
  - [Dados Crus](https://github.com/EltonGS/BC_DS_projeto_modulo_3/blob/main/Notebooks/dados_crus.ipynb) - Notebook com os dados sem nenhum tratamento.
  - [Tratamento dos Dados](https://github.com/EltonGS/BC_DS_projeto_modulo_3/blob/main/Notebooks/tratamento_dados.ipynb) - Notebook com as manipulações que foram realizadas com os dados.
  - [Análise Exploratória](https://github.com/EltonGS/BC_DS_projeto_modulo_3/blob/main/Notebooks/analise_exploratoria.ipynb) - Notebook com análise exploratória dos dados e verificação das hipóteses.
  - [Modelo de Previsão](https://github.com/EltonGS/BC_DS_projeto_modulo_3/blob/main/Notebooks/modelo_prophet.ipynb) - Notebook com a criação do modelo de previsão utilizando a biblioteca Facebook Prophet.
  
#Referências:
  
- [Brasil.IO](https://brasil.io/dataset/covid19/caso_full/)
- [Alura](https://www.alura.com.br/artigos/series-temporais-e-suas-aplicacoes)
- [Diário do Transporte](https://diariodotransporte.com.br/2020/05/19/quatro-cidades-do-abc-paulista-decretam-antecipacao-do-feriado-de-corpus-christi-e-tres-aguardam-aprovacao-do-legislativo/)
- [Folha](https://agora.folha.uol.com.br/sao-paulo/2021/03/veja-como-ficam-os-feriados-antecipados-nas-cidades-do-abc.shtml)
- [Fundação do ABC](https://fuabc.org.br/noticias/santo-andre-chega-a-marca-de-100-mil-vacinados-contra-covid-19-no-aniversario-da-cidade/)
- [Documentação Facebook Prophet](https://facebook.github.io/prophet/)
- Fonte Imagem: https://www.pfizer.com.br/sua-saude/covid-19-coronavirus
