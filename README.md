# Geopandas

Detalhes do Programa
O script realiza as seguintes operações:

- Importa as bibliotecas necessárias, incluindo GeoPandas, Rtree, PyGEOS, Mapclassify, Geobr e Folium.
- Lê dados de municípios usando geobr.read_municipality() para obter todos os municípios do Brasil em 2020.
- Filtra os dados para obter informações específicas sobre Brasília (BSB).
- Cria um mapa Folium para exibir os dados do município de Brasília, usando o estilo "CartoDB positron".
- Lê dados de escolas usando geobr.read_schools() para obter informações sobre escolas em 2020.
- Realiza uma junção espacial (gpd.sjoin()) para associar escolas localizadas em Brasília aos dados do município.
- Cria um mapa interativo com camadas de dados de escolas sobrepostas aos dados do município de Brasília.
- Personaliza o estilo e as informações exibidas nos popups e na legenda do mapa.
