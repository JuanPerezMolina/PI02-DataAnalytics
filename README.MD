
<h1 align='center'>
 <b>PROYECTO INDIVIDUAL Nº2</b>
</h1>
 
# <h1 align="center">**`Mercado bursátil`**</h1>
## <h1 align="center">**Juan Jose Perez**</h1>



## **Descripción del problema **

### **Contexto**

Se requiere el análisis del mercado de inversiones con el fin de asesorar a una empresa que requiere los servicios de un analista de datos para determinar la mejor opción de inversión para un determinado capital. 
  
Para este estudio se cuenta con los datos de los precios de las acciones del SP500 (Standar & Poor 500) 





### `Posible solución`

-1 Definir el objetivo de inversión: El primer paso es conocer cuál es el objetivo de inversión de la persona que quiere invertir el millón de dólares en acciones del sector tecnológico. ¿Es a largo plazo o a corto plazo? ¿Cuál es el nivel de riesgo que está dispuesto a asumir? ¿Cuál es su horizonte de inversión? Esto permitirá definir un marco de referencia para el análisis.

-2 Recopilar los datos: Una vez definido el objetivo de inversión, se recopilarán los datos que se utilizarán para el análisis. En este caso, queremos utilizar los precios de las acciones del S&P 500 desde el año 2000. Es importante que estos datos sean precisos y actualizados.

-3 Identificamos las KPIs: A continuación, se deben identificar las variables relevantes que se utilizarán para el análisis. En este caso, la variable principal serían los precios de las acciones del S&P 500. Sin embargo, también se pueden incluir otras KPIs, como el rendimiento de las acciones en el sector tecnológico, el desempeño del mercado en general y las noticias económicas relevantes.

-4 Analizar los datos: Con los datos recopilados y las KPIs identificadas, se puede comenzar a analizar los datos utilizando técnicas de ciencia de datos. Se pueden utilizar técnicas de análisis estadístico para identificar patrones y tendencias en los datos, y técnicas de aprendizaje automático para crear modelos predictivos que puedan ayudar a tomar decisiones de inversión.

-5 Presentaremos los  resultados del análisis a la persona o empresa que desea invertir el capital necesario en acciones del sector tecnológico. Es importante presentar los resultados de manera clara y concisa, y explicar cómo se llegó a las conclusiones y recomendaciones de inversión. También es importante recordar que la inversión siempre conlleva riesgos, y que los resultados del análisis no garantizan el éxito en la inversión.

### `Puntos importantes` 

En lugar de estudiar las acciones de las 500 empresas que conforman el S&P 500, se ha decidido enfocar el análisis en cinco empresas específicas del sector tecnológico. Esta decisión se debe a diferentes motivos, como la especialización en este sector o la creencia de que estas empresas tienen un potencial de crecimiento mayor que otras en el índice. Al reducir el universo de estudio a solo cinco empresas, el análisis puede ser más específico y enfocado, lo que permitirá obtener una visión más detallada del desempeño de estas empresas en el mercado.

El marco de tiempo seleccionado para el estudio será a partir del año 2012. Esto se debe a que no se cuenta con datos anteriores a esa fecha. El año 2012 también es un punto de inflexión en el mercado de tecnología, donde las empresas de este sector comenzaron a tener un papel más importante en el mercado global. Al limitar el marco de tiempo a partir de esta fecha, se pueden identificar tendencias y patrones específicos en el comportamiento de las empresas seleccionadas.

Los KPI (Key Performance Indicators) a estudiar serán el rendimiento, la volatilidad y el riesgo. Estos KPI son fundamentales para evaluar el desempeño de las empresas seleccionadas en el mercado de tecnología. El rendimiento permite medir la rentabilidad de la inversión, la volatilidad mide la fluctuación de los precios de las acciones y el riesgo mide la probabilidad de perder dinero en la inversión. Al analizar estos KPI, se puede determinar el grado de éxito y estabilidad financiera de las empresas en el sector tecnológico, lo que permitirá tomar decisiones informadas de inversión.

### `Calculos importantes`

Para calcular el retorno anual a partir de los precios de cierre de las acciones de estas cinco empresas, se sigió los siguientes pasos:

Se obtuvo los precios de cierre: primero se recopiló los precios de cierre diarios de las acciones de las cinco empresas seleccionadas durante el período de tiempo elegido (a partir de 2012). Esto se hizo conla API   de Yahoo Finance, la plataforma de negociación de valores , sitio web especializado en finanzas.

Se calculó el retorno diario: A continuación, calculé el retorno diario de las acciones de cada empresa. Para ello utilizé la siguiente fórmula: ((Precio de cierre actual / Precio de cierre anterior) - 1) x 100. Esta fórmula permite calcular el cambio porcentual en el precio de las acciones de un día a otro.

Calculé el retorno anual: Una vez que se tienen los retornos diarios de las acciones de cada empresa, pude sumar todos los retornos diarios para cada año y dividir el resultado por el número de días hábiles en ese año. Esto me dió como resultado el retorno anual de las acciones de cada empresa. La fórmula para calcular el retorno anual es la siguiente: ((1 + retorno diario promedio)^días hábiles en el año) - 1.

Interpretar los resultados: Una vez que se han calculado los retornos anuales de las acciones de cada empresa, se pueden comparar los resultados entre ellas y con el mercado de tecnología en general. Esto permitió identificar cuáles empresas han tenido un mejor desempeño y cuáles han sido menos exitosas en términos de rendimiento. También se pudo identificar tendencias y patrones en el comportamiento de las empresas a lo largo del tiempo, lo que puede ser útil para tomar decisiones informadas de inversión en el futuro.




