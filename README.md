# adf-tarea2-datawarehouse-vacunacion

* Descripcion del proyecto *

** Estructura ** 
	- Dataset
	- Modelos (consultas sql para crear el datawarehouse)
	- Terraform
	- Videos	

** Stack Azure **
	- Grupo de Recurso
	- Storage accounts - datalake gen 2
	- sql database
	- azure datafactory

** Arquitectura **
	- Bronze -> datos crudos
	- Silver -> limpieza e integracion de los datos
	- gold -> creacion del datawarehouse etl & pipelineas

** Solucion **
	
	*** Metodo 1 ***
		- bronze -> Storage accounts - datalake gen 2
		- silver -> schema silver - dw_ventas
		- gold -> schema gold y datawarehouse dw_ventas
