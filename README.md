Trabajo Final Grupal: Bank Subscription
Universidad Tecnológica Nacional, Buenos Aires
Ingeniería Industrial
Ciencia de Datos - Curso I5521

Alumnos: Acosta, Bruno y Bartolomeo, Agustin

clusterai2023
En este repositorio se publica el trabajo practico realizado para la clase de ciencia de datos del año 2023

Un banco quiere predecir cuantos clientes se suscribirán a una campaña de marketing. Para ello, comparten un data set con una cartera de clientes de 45,211 personas con 17 variables que muestran algunas características de los clientes en el banco.

Se realizará un estudio profundo del data set, para entender con que datos estamos trabajando y cuales son las tendencias de sus datos; seguido de una transformación de las variables. Con el data set transformado, se entrenarán varios modelos de machine learning con el objetivo de encontrar el que predice si un cliente se va a subscribir o no de la mejor manera posible.

Descripción de archivos:
bank_subscription (1).csv
En este archivo csv se encuentran los datos con los que se trabajan en este proyecto. El mismo tiene las siguientes columnas:

Age: Edad del cliente
Job: Tipo de empleo del cliente
Martial Status: Estado civil
Education: Educación máxima alcanzada por el cliente
Credit: Si tiene deuda de crédito o no
Balance (euros): Promedio de saldo en la cuenta en el año
Housing loan: Si tiene seguro de hogar o no
Persona loan: Si tiene prestamos o no
Contact: Tipo de contacto del cliente (celular o teléfono)
Last Contact Day: Ultimo día de contacto con el cliente en el mes
Last Contact Month: Ultimo mes de contacto con el cliente en el año
Last Contact Duration: Duración del último contacto con el cliente medido en segundos
Campaign: Cantidad de contactos al cliente durante esta campaña, incluye el último contacto.
Pdays: Cantidad de dias que pasaron del último contacto con el cliente de una campaña anterior. -1 significa que no hubo contacto previo
Previous: Cantidad de contactos previos a esta campaña para cada cliente
Poutcome: Performance de la campaña de marketing anterior para este cliente
Subscription: Si el cliente accede a la campaña (1) o no (0). Variable a predecir.
clusterai_bruno_acosta_transformaciones.ipynb
En este archivo se encuentran todas las funciones que transforman el data set para que pueda ser procesado por los modelos de machine learning. Se importan por medio de la libreria ipyn.

clusterai_Agustin_Bartolomeo_eda.ipynb
En este archivo se encuentra el análisis exploratorio de los datos.

clusterai_Agustin_Bartolomeo_transformations.ipynb
En este archivo se encuentra el entrenamiento y análisis de varios modelos de machine learning, seguido por una reducción de dimensionalidad y nuevo entrenamiento de modelo.

clusterai_reporte_Bartolomeo.pdf
Este es el reporte final donde se detallan los algoritmos usados y los resultados obtenidos.
