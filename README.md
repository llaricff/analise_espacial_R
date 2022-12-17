# Análise Espacial utilizando o R

## Projetos desenvolvidos durante meu MBA em Data Science & Analytics

Para análise espacial, vamos aprender diversas técnicas de plotagem e observação. 

SHAPEFILES

Vamos iniciar carregando um shapefile do Estado de São Paulo. 

shp_sp <- readOGR(dsn = "shapefile_sp", layer = "estado_sp")

Um shape file possui várias caracteristicas para plotagem espacial. Para termos acesso a sua base de dados, basta comandar:

shp_sp@data

![Rplot_1](https://user-images.githubusercontent.com/96158594/208255498-d75b6d27-02ef-4228-bf53-265fd447fd91.png)

Aqui está a sua plotagem básica:

![Rplot_2](https://user-images.githubusercontent.com/96158594/208255531-bb7e82e6-8f72-41dc-81ae-ac8523459cf2.png)

E aqui a plotagem dos dados que o shapefile nos oferece:

![Rplot_3](https://user-images.githubusercontent.com/96158594/208255602-fa31a747-8172-472c-9eb6-7da77b6fe742.png)

Com o aperfeiçoamento das técnicas e utilizando os pacotes corretos, podemos chegar a essa plotagem:

![Rplot_4](https://user-images.githubusercontent.com/96158594/208255682-13e8be7f-d25c-480a-9231-1aa89d3048ff.png)

SIMPLE FEATURES E SHAPEFILES

No script sobre os simple features e shapefiles, vamos analisar estes tipos de objetos sendo analisados conjuntamente. Aqui faremos a análise da quantidade de shoppings que existe na região central de São Paulo:

![Rplot_5](https://user-images.githubusercontent.com/96158594/208255863-241d0927-92e7-4b97-91e0-bbdf2fc60b6c.png)

E por fim, utilizando os métodos de BUFFER ANALYSIS e KERNEL DENSITIES, podemos chegar à uma análise espacial que nos oferece a densidade de shoppings e sua influência da região central de SP:

![Rplot_6](https://user-images.githubusercontent.com/96158594/208255977-0cd62a15-2b92-4216-82b3-c1f3c07648fe.png)

RASTER

Para aprender a lidar com objetos RASTER, vamos fazer uma análise do relevo do litoral paulista. O R nos permite plotagems bem apuradas:

![Rplot_6](https://user-images.githubusercontent.com/96158594/208256528-6cc2c63c-6037-4ca3-a0df-9d1aba3fa908.png)

MODOS DE VISUALIZAÇÃO

Aqui iremos explorar os diversos modos de visualização que o R nos permite. 

CASO R

Este script serve para consolidarmos tudo o que aprendemos. Neste script iremos elaborar um mapa interativo sobre a pobreza em Santa Catarina:

https://user-images.githubusercontent.com/96158594/208256737-342c4994-ce97-4193-9cfc-ff57ba52df5e.mp4

Todos os scripts com detalhamento das atividades estão nesta pasta! Aproveitem!
