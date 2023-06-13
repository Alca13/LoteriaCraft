# LoteriaCraft
Generador de cartones de Loteria

#Descripción
Este sistema permite a los clientes generar rápidamente cartones de lotería mexicana sin tener que preocuparse por los detalles técnicos. Es una herramienta eficiente y fácil de usar que brinda la emoción y la diversión del juego de lotería de manera conveniente.

#Codigo
El Codigo esta basado en Python, para mayor comodidad del usuario al tener que generar, se traslado el software a una dependencia de Google Colab, en donde realiza el mismo seguimiento y funcion.

#Funcion
1.- El sistema crea y verifica la creacion de archivos necesarios para la ejecucion como librerias
2.- Se ejecuta el entorno de carga y verificacion de las imagenes que seran parte del carton de loteria,
		#Nota
		*El procesador de imagen ajusta a una resolucion de 173x281px esto para establecer un rango de espacio entre las imagenes y poner 4x4 en cartones
		*El sistema renombra todos los archivos para de 1.jpg..2..3.png.... para evitar un colapso en la ejecución 
		*El sistema por el momento solo aceptan 51 imagenes, debe de ser exacto no una menos y no una mas, ya que ´pr el momento se esta trabajando en conocer las cantidades exactas de las imagenes tener las iamgenes que deseas procesar
		
