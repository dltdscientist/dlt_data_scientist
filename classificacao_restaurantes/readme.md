Classificação de Restaurantes
Contexto
O ano de 2020 passou e muitos resumos deste ano pandêmico foram criados, por exemplo, na forma de classificações. Essa lista (ou na verdade 3 listas) foi criada pela revista "Restaurant Business". 
No site você encontra apenas informações básicas sobre restaurantes classificados.
Os dados foram obtidos por meio de web scraping, ou seja, download de dados com a utilização de código de programação baseado no código do site. 
Neste caso, o pacote "rvest" da linguagem de programação R foi usado junto com o add-on do navegador "SelectorGadet" para facilitar o trabalho com o site.
Os dados foram baixados de https://www.kaggle.com/michau96/restaurant-business-rankings-2020 em 20 de fevereiro de 2021 com três datasets descrevendo 3 classificações: top 250, top 100 indenents e future 50, criando assim 3 tabelas, onde o restaurante é descrito por várias variáveis em cada coluna.