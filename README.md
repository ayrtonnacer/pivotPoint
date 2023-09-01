# Proyecto de Cálculo de Puntos de Pivote en Python
![image](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue) ![image](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)


Este proyecto se centra en el cálculo de puntos de pivote (Pivot Points) en el mercado financiero utilizando Python. Los puntos de pivote son niveles significativos en el gráfico de cotizaciones que actúan como indicadores de soporte y resistencia. Estos niveles se calculan a partir de los máximos, mínimos y cierres del período anterior y se utilizan para estimar los futuros niveles de soporte y resistencia.

## Descripción

Este proyecto utiliza varias bibliotecas de Python, como [yfinance](https://pypi.org/project/yfinance/), [mplfinance](https://pypi.org/project/mplfinance/), y [pandas](https://pandas.pydata.org/), para realizar las siguientes tareas:

1. Obtener datos históricos de precios de un activo financiero (por ejemplo, acciones o criptomonedas) desde Yahoo Finance.
2. Calcular los puntos de pivote y los niveles de soporte y resistencia en función de esos datos.
3. Generar un gráfico de velas (candlestick chart) que muestra los precios históricos y los niveles de soporte/resistencia calculados.
4. Visualizar el gráfico resultante para ayudar en el análisis técnico de los movimientos de precios.

## Uso

Para utilizar este proyecto, sigue estos pasos:

1. Clona o descarga este repositorio en tu máquina local.

2. Asegúrate de tener Python instalado en tu sistema. Si no lo tienes, puedes descargarlo desde Licencia
Este proyecto está bajo la licencia MIT, lo que significa que puedes utilizarlo, modificarlo y distribuirlo de acuerdo con los términos de esa licencia.

3. Instala las bibliotecas necesarias ejecutando el siguiente comando:

   ```bash
   pip install mplfinance yfinance pandas
   
4.  Ejecuta el script principal, que calculará los puntos de pivote y generará el gráfico de velas. Puedes personalizar el activo financiero, el rango de fechas y otros parámetros según tus necesidades.

5. El gráfico resultante se mostrará en pantalla para su análisis.


## Licencia
Este proyecto está bajo la [licencia MIT](https://opensource.org/license/mit/), lo que significa que puedes utilizarlo, modificarlo y distribuirlo de acuerdo con los términos de esa licencia.

