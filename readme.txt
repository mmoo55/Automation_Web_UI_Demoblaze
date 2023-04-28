Este archivo contiene los pasos para realizar la ejecución de la prueba. Se recomienda usar Pycharm
Siga a detalle cada uno de los pasos siguientes:
    Instalación de paquetes necesarios para el proyecto:
        1 Instalar pytest-html
		    pip install pytest-html
	    2 Instalar selenium
		    pip install selenium
	    3 Instalar chromedriver_autoinstaller
	    	pip install chromedriver_autoinstaller
	    4 Instalar edgedriver_autoinstaller
	    	pip install edgedriver_autoinstaller
	    5 Instalar geckodriver_autoinstaller
	    	pip install geckodriver_autoinstaller
	    6 Instalar dotenv
	        pip install python-dotenv

	Ejecución de la prueba:
	    1. Importar el proyecto.
	    2. La ejecución de la prueba se puede realizar de diferentes maneras:
	        - Una vez dentro del proyecto y si esta utilizando Pycharm, presione las teclas Mayús+F10.
	        - Si esta usando Pycharm, dentro del proyecto dirigirse al directorio:
	                /Automation_Web_UI/test_suite/test_purchase.py
	          a continuación presione el ícono "run" (flecha verde)
	        - Abra una terminal en la ruta del proyecto o si esta en IntelliJ IDEA utilice la terminal que viene
	          integrada, a continuación utilice el siguiente comando:
	                pytest .\test_suite\test_purchase.py --html=.\reports.\test_purchase.html

    Para generar el reporte realizar la siguiente acción:
        Abra una terminal en la ruta del proyecto o si esta en Pycharm utilice la terminal que viene integrada,
        a continuación utilice el siguiente comando:
                    pytest .\test_suite\test_purchase.py --html=.\reports.\test_purchase.html

    Se puede visualizar el reporte de diferentes maneras:
        - Una vez ejecutado el comando, devolverá en la terminal un enlace, el cual puede hacer click o copiar y pegarlo
	      en el navegador.
	    - Dirigirse al directorio /Automation_Web_UI/reports/test_purchase.html, donde encontrará el archivo ".html"