# reusable_blocks_d3
Aprender a usar y crear bloques reusables para crear gráficos con d3. Impartido por el profesor John Alexis Guerra de la Universidada de los Andes:

Para la primera parte usaremos un bloque y código creados por [Mike Bostock](https://en.wikipedia.org/wiki/Mike_Bostock) en su [explicación](https://bost.ocks.org/mike/chart/) de como crear nuestros propios bloques.  :

1. Para usar su ejemplo debemos usar [su](https://bost.ocks.org/mike/chart/time-series-chart.js) código de creación de gráfico de series de tiempo
2. Debe buscar un bloque donde se pueda generar este gráfico. Hay una serie de bloques muy interesantes en esta [url](https://blockbuilder.org/search?thumb=true), Par este caso vamos a elegir un bloque de [gráfico de barras](https://blockbuilder.org/mbostock/946ddf8a32b3b660ffd8) hecho por Mike Bostock. **NOTA:** tenga encuenta que al final del año esta página solo será para búsqueda de blosques. Ya que la constucción de los mismos se puede hacer en [Observable](https://observablehq.com/)
3. También vamos a necesitar un [archivo de datos](https://blockbuilder.org/mbostock/3885304) que es con el se renderiza este bloque. Este archivo es llamado "data.tsv"

Si tiene a su disposición la librería `http-server@0.12.3` puede activar el bloque con:
* `http-server barChart/`
