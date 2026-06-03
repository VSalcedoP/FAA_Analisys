# Visualización de datos - Práctica
## Autor: Virgilio Salcedo Polo
### Asignatura: Visualización de datos

#### <ins>Organización del proyecto</ins> ####

El proyecto ha sido realizado en R-Studio+Quarto

- Los Factores Detrás de los Incidentes Aéreos
  - data
	- faa_incidents_limpios.rds
	- faa_phase_analysis.rds
  - data_raw
	- faa_incidents_data.csv
  - output
	- PR_files
		- libs
			- bootstrap
			- clipboard
			- crosstalk-1.2.2
			- htmltools-fill-0.5.9
			- htmlwidgets-1.6.4
			- jquery-3.5.1
			- plotly-binding-4.12.0
			- plotly-htmlwidgets-css-2.25.2
			- plotly-main-2.25.2
			- quarto-html
			- typedarray-0.1
	- PR.html
	- styles.css
  - Scripts_MD
	- Data_cleanup.Rmd
	- Data_cleanup.html
  - README.md
  

#### <ins>Descripción del proyecto</ins> ####
Esta PEC se corresponde con la práctica de la asignatura de "Visualización de datos" del master "Ciencia de Datos" de la UOC.
Su objetivo es crear una visualización sobre incidentes aereos en base a datos proporcionados por la FAA que, permita responder a las siguientes preguntas:
- ¿Cuáles son las características de las aeronaves involucradas en los accidentes e incidentes? Analiza la distribución por fabricante (Aircraft Make), modelo (Aircraft Model), número de motores (Nbr of Engines) y tipo de motor (Engine Group Code).
- ¿En qué fases del vuelo (Flight Phase) se producen más accidentes e incidentes?
- A partir de este análisis, ¿qué recomendaciones podrías hacer a los operadores para mejorar la formación de los pilotos y reducir la accidentalidad en esas fases?
- ¿En qué casos los accidentes tienen víctimas mortales (Total Fatalities > 0)? ¿Cuáles son los factores comunes en los sucesos con resultado de muerte?
- ¿Hay operadores (Operator) que concentran más accidentes o incidentes que otros? En caso afirmativo, ¿qué implicaciones tiene esto para sus programas de formación de pilotos y mantenimiento de aeronaves?

#### <ins>Visualización</ins> ####
La carpeta "output" contiene todos los archivos necesarios para visualizar el resultado del estudio. Una vez descargada, únicamente hay que abrir el archivo PR.html con el navegador.
* Se ha comprobado su correcto funcionamiento en Chrome Versión 148.0.7778.179
