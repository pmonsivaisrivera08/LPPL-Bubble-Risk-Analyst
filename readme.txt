LPPL Bubble Risk Analyst
Un proyecto de análisis de econofísica para detectar y cuantificar el riesgo de burbujas en activos financieros utilizando el Modelo de Ley de Potencia Log-Periódica (LPPL).
Este repositorio contiene un notebook de Python que implementa el modelo LPPL para ajustarse a series de tiempo de precios de activos y calcular indicadores clave de riesgo, como el tiempo crítico (t_c) y la métrica de riesgo de burbuja de Johansen-Ledoit-Sornette (JLS).
🌟 Características Clave
* Implementación del Modelo LPPL: Código funcional para el modelo de Ley de Potencia Log-Periódica, una herramienta avanzada para el análisis de burbujas.
* Análisis Automático de Datos: Obtiene datos históricos de precios directamente desde Yahoo Finance (yfinance).
* Análisis de Riesgo: Calcula el tiempo crítico (t_c) —la fecha de colapso pronosticada— y la métrica de burbuja JLS, proporcionando una cuantificación del riesgo.
* Visualización Completa: Genera gráficos interactivos con Matplotlib, mostrando el ajuste del modelo, los datos en escalas logarítmicas y lineales, y los residuos para una evaluación de la calidad del ajuste.
* Personalizable: Permite al usuario seleccionar cualquier activo financiero disponible en Yahoo Finance para el análisis.
💻 Instalación y Uso
1. Clona el repositorio:
git clone [https://github.com/pmonsivaisrivera08/LPPL-Bubble-Risk-Analyst.git](https://github.com/pmonsivaisrivera08/LPPL-Bubble-Risk-Analyst.git)
cd LPPL-Bubble-Risk-Analyst

2. Instala las dependencias necesarias:
pip install pandas numpy scipy matplotlib yfinance

3. Ejecuta el notebook:
Abre el archivo LPPL_Bubble_Risk_Analyst.ipynb en Jupyter Notebook o Google Colab y ejecuta las celdas una por una para ver el análisis completo.
⚠️ Aviso Legal
Este proyecto es una herramienta de investigación y no debe ser utilizado para tomar decisiones de inversión. El modelo LPPL es una herramienta de análisis de riesgo que se basa en la identificación de patrones históricos. No es una predicción infalible del mercado y los resultados deben interpretarse con precaución. El autor y los colaboradores no son responsables de ninguna pérdida o daño financiero resultante del uso de este código.
🤝 Contribuciones
Las contribuciones son bienvenidas. Siéntete libre de abrir un issue o enviar un pull request con mejoras, correcciones de errores o nuevas funcionalidades.
📄 Licencia
Este proyecto está bajo la Licencia MIT.