# Data Mining From Gmail

Este es un programa escrito en Python utilizando el Jupyter Notebook. El programa se conecta a una cuenta de correo electrónico y descarga todos los correos recibidos en un período de tiempo específico. Luego filtra los correos para detectar fallas y reposiciones. Los datos necesarios se extraen de los correos y se almacenan en dos dataframes diferentes. Finalmente, los dos dataframes se exportan a un archivo csv/excel.

📝🐍 Proyecto en Jupyter Notebook de Python para acceder a una cuenta de correo electrónico, extraer información y exportarla a un archivo CSV o Excel.

## Este proyecto utiliza los siguientes módulos:

* `imaplib` para ingresar a los correos.
* `re` para realizar búsquedas de texto en el cuerpo del correo.
* `pandas` para trabajar con dataframes y exportarlos a hojas de cálculo.
* `email` para procesar los correos electrónicos.

## El programa realiza las siguientes acciones:

1. Acceder a una cuenta de correo electrónico.
1. Guardar en un dataframe todos los correos de un determinado periodo.
1. Cerrar la sesión.
1. Filtrar en el dataframe los correos de detectores.
1. Crear un dataframe para fallas y otro para reposiciones.
1. Extraer la información necesaria de cada correo y agregarla a los dataframes correspondientes.
1. Exportar los dos dataframes a un archivo CSV o Excel.
