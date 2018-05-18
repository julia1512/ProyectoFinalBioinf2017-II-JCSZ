Julia Carrasco Zanini Sánchez

## Avance 3
- He empezado a hacer el análisis de componentes principales para los Marcadores de Ancestría Informativos (AIMs) con el paquete `SNPstats`, utilizando el comando `eigen`.
- He hecho gráficas para ver la proyección de los puntos en distintos componentes principales.
- He hecho algunos scripts en `R` para analizar la asociación de los SNPs en genes involucrados en el metabolismo de unidades de carbono con ciertos metabolitos en suero.
- He empezado a organizar los directorios del proyecto de acuerdo a la organización vista en clase:
	- Dentro de `Bin` estarán 3 scripts básicamente:
		1. El primer script será uno en bash que llamará al software `PLINK` será para codificar los datos de los alelos que se encuentran reportados como bases (A,C,T,G) mediante 0,1,2; dependiendo del número de *alelos de riesgo*.
		2. El segundo script será en `R` para hacer el análisis de componentes principales de los AIMs
		3. El tercer script será en `R` para hacer los análisis de asociación de los SNPs conn metabolitos maternos. 

	- Dentro de `Data` estarán las bases de datos que contienen los datos de los SNPs y de las determinaciones séricas de los metabolitos de cada paciente listos para leerse por los scripts de R.
	- Dentro de `Figures` estarán los archivos de las figuras y los renders del código utilizado para generar las figuras.
	- Dentro de `Meta` estará la base de datos de los alelos reportados como bases y los archivos secundarios que necesita `PLINK` para correr los comandos que se utilizarán. 

- [Avance del README](https://github.com/julia1512/ProyectoFinalBioinf2017-II-JCSZ/blob/master/README.md)