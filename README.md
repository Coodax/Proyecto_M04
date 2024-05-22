# README.md

## Despliegue de la Aplicación 

Breve guía:
La aplicación usa Flask y puede funcionar en dos modos: modo local (utilizando un archivo XML descargado) y modo remoto (obtenido directamente de la web de La Vanguardia).

## Requisitos Previos

Como requisito previo es importante tener Python instalado en el sistema.

## Configuración del Entorno Virtual

    1. Clonar o descargar el repositorio en el sistema.
    2. Navegar a la carpeta del proyecto.
        - cd nombre_carpeta_proyecto
    3. Crear un entorno virtual para nuestro proyecto. En mi caso por la version que tengo de Python tengo que utilizar 'venv'.
        - python -m .venv venv
    4. Activar el entorno virtual.
        - En mi caso al tener Windows usare el siguiente comando: venv\Scripts\activate

## Instalación de Dependencias

Una vez activado el entorno virtual se instalarán las dependencias:
    - pip install -r requirements.txt

## Inicio de la Aplicació

Para iniciar la aplicación hay que hacerlo con el siguiente comando:
    - python app.py
Después de hacer el comando (en teoría) se puede ver la aplicación en el navegador web escribiendo 'http://localhost:5000'

## Modo de uso

Como he dicho al principio hay dos modos de uso:

* Modo Local:
    - Aquí, en este modo, carga el archivo XML desde la máquina local.
* Modo Remoto:
    - En este modo, se obtiene el archivo directamente desde la web de La Vanguardia (es necesario tener conexión a internet).

 ## Recursos Adicionales
Documentación de Flask:[Documentación de Flask](https://flask-es.readthedocs.io/).
¿Qué son los entornos virtuales?: Entornos Virtuales en Python [Entornos Virtuales en Python](https://docs.python.org/es/3/tutorial/venv.html).
