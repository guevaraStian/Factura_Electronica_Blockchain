
<h1 style="font-size: 3em; color: #FF0000;">•  ALMACENAMIENTO DE FACTURAS ELECTRONICAS CON BLOCKCHAIN</h1> 


![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![MongoDB](https://img.shields.io/badge/-MongoDB-13aa52?style=for-the-badge&logo=mongodb&logoColor=white)
![JavaScrip](https://shields.io/badge/JavaScript-F7DF1E?logo=JavaScript&logoColor=000&style=flat-square)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=Flask&logoColor=white) 
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)


Los pasos para poner en ejecución son los siguientes
Ir a la pagina web de Python y Git, luego descargarlo para tu sistema operativo, escoger la opción "add path" con el fin de poder ejecutar comandos de Python en la terminal de comandos.

```Pagina web
https://www.python.org/downloads/
https://git-scm.com/downloads
```
Vamos a la pagina web de MongoDb y descargamos el ejecutable y lo ejecutamos, luego de finalizar la instalación abrimos el Compass de MongoDb.

```Pagina web
https://www.mongodb.com/es/products/tools/compass
```
Luego de tener instalado Python podemos ejecutar los siguientes comandos en la carpeta del proyecto.

```Terminal de comandos
python --version
pip --version
git init
git clone https://github.com/guevaraStian/Factura_Electronica_Blockchain.git
cd Factura_Electronica_Blockchain
git push origin master
```

Luego ingresamos a la carpeta creada e instalamos las librerias y ejecutamos el proyecto.

```Terminal de comandos
pip install flask werkzeug lxml hashlib pymongo
python FEBlockchain.py
```


Luego que el proyecto ya se este ejecutando, podemos verlo funcionar en la siguiente ruta url local con el puerto asignado 5000

```Pagina web
http://localhost:5000
http://127.0.0.1:5000
```

