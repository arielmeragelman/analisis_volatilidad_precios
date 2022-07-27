# analisis_volatilidad_precios

El proyecto inicia con un proceso de web scrapping [ scrapper_lxml.ipynb  ] que de forma diaria recopila información desde 3 supermercados seleccionados y para productos que elegimos.
Esta informacion impacta en una Base de datos mysql que esta corriendo localmente


Partiendo de la informacion de la base de datos podemos realizar un extract para formar un set de datos con el cual trabajar.

Sobre esto trabaja el archivo [ convertir_sql_en_data_v1.ipynb ] el cual genera una matriz de información a partir del extract de la base de datos, limpia registros invalidos o que no pueden ser utiles para nuestro analisis, y le suma informacion de fuentes externas por ejemplo el valor del dolar.

