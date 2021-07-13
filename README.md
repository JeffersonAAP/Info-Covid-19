![Banner](https://i.ibb.co/H7Psv95/covid19.jpg)
# Título del proyecto:

#### Info Covid-19
***
## Índice
1. [Características](#caracter-sticas-) 📋
2. [Contenido del proyecto](#contenido-del-proyecto) 🗄️
3. [Tecnologías](#tecnologías) 💻
4. [IDE](#ide) 📝
5. [Instalación](#instalación) 💿
6. [Demo](#demo) 📲
7. [Autor(es)](#autores) 👨
8. [Institución Académica](#institución-académica) 🏫
9. [Referencias](#referencias) 🖋️
***


#### Características:

  - Proyecto con lectura de datos JSON mediante AJAX
  - Carga dinámica del JSON 
  - Archivo JSON de ejemplo: [ver](https://www.datos.gov.co/resource/gt2j-8ykr.json)
  - Versión: [![Versión](https://img.shields.io/badge/1.0-lightgrey)](#)
***
  #### Contenido del proyecto

| Archivo      | Descripción  |
|--------------|--------------|
| [index.html](https://gitlab.com/jeffersonandresap/info-covid-19/-/blob/master/index.html) | Archivo principal del proyecto|
| [html/home.html](https://gitlab.com/jeffersonandresap/info-covid-19/-/blob/master/html/home.html) | Archivo HTML que describe el COVID y sus síntomas [(CORONAVIRUS (COVID-19), 2020)](#referencias)|
| [html/casos](https://gitlab.com/jeffersonandresap/info-covid-19/-/blob/master/html/casos.html) | Archivo HTML con el proceso de lectura del JSON y sus funciones adicionales para la impresión de resultados [(Casos positivos de COVID-19 en Colombia, 2020)](#referencias)|
| [css/style.css](https://gitlab.com/jeffersonandresap/info-covid-19/-/blob/master/css/style.css) | Archivo CSS con el estilo utilizado en el proyecto|

  
***
#### Tecnologías

  - [![HTML5](https://img.shields.io/badge/HTML5-orange)](https://developer.mozilla.org/es/docs/Web/Guide/HTML/HTML5)
  - [![CSS](https://img.shields.io/badge/CSS-blue)](https://developer.mozilla.org/es/docs/Web/CSS)
  - [![JavaScript](https://img.shields.io/badge/JavaScript-green)](https://developer.mozilla.org/es/docs/Web/JavaScript)
  


Puede hacer uso del siguiente marco conceptual:

  - [Vídeo explicativo sobre como procesar archivos JSON con AJAX](https://www.youtube.com/watch?v=M4LaQ3KUGOM)
  - [Guía de Mozzilla JSON](https://developer.mozilla.org/es/docs/Learn/JavaScript/Objects/JSON)
  
  ***
#### IDE

- [![Sublime-Text-3](https://img.shields.io/badge/Sublime-Text%203-lightgrey)] El proyecto se desarrolló usando sublime text 3, es un editor de texto para código en diferentes lenguajes, se destaca su versatilidad para el manejo de marcas y autocompletado [(Kinder, 2013)](#kinder-k-2013-sublime-text-one-editor-to-rule-them-all-linux-journal-2013232-2).
![IDE](https://sc.filehippo.net/images/t_app-cover-m,f_auto/p/12cc2ea4-9aa3-11e6-b866-00163ec9f5fa/4046653434/sublime_text-screenshot.png)

***
### Instalación

- Proyecto-> [descargar](https://gitlab.com/jeffersonandresap/info-covid-19/-/archive/master/info-covid-19-master.zip). Carpeta comprimida que contiene todos los archivos del proyecto.
- XAMPP-> [descargar](https://www.apachefriends.org/es/download.html).
El software es necesario para que AJAX pueda ejecutar la carga del JSON mediante el uso del servidor web Apache que se aloja de manera local, de lo contrario el usuario no podra visualizar la tabla con los datos del JSON.


```sh
-Ejecutar XAMPP e iniciar el servidor Apache.
-Cargar la carpeta del proyecto en la carpeta htdocs donde se encuentra instalado XAMPP.
-Invocar página localhost/NOMBRECARPETAPROYECTO/index.html desde cualquier navegador.
```

***
### Demo

Para ver la demo de la aplicación puede dirigirse a: [Info Covid-19](https://jeffersonandresap.gitlab.io/info-covid-19).

***
### Autor(es)
Proyecto desarrollado por Jefferson Alvarez (<jeffersonandresap@ufps.edu.co>).


***
### Institución Académica   
Proyecto desarrollado en la Materia programación web del [Programa de Ingeniería de Sistemas] de la [Universidad Francisco de Paula Santander]


   [Programa de Ingeniería de Sistemas]:<https://ingsistemas.cloud.ufps.edu.co/>
   [Universidad Francisco de Paula Santander]:<https://ww2.ufps.edu.co/>
   
   ***
### Referencias
   

###### Kinder, K. (2013). Sublime text: one editor to rule them all?. Linux Journal, 2013(232), 2.
###### CORONAVIRUS (COVID-19). (2020). CORONAVIRUS (COVID-19) [Reporte y Tablero de control]. Minsalud. Recuperado de: https://www.minsalud.gov.co/salud/publica/PET/Paginas/Covid-19_copia.aspx [2020]
###### Casos positivos de COVID-19 en Colombia. (2020). Casos positivos de COVID-19 en Colombia [Reporte y Tablero de control]. Gov.co - Datos Abiertos. Recuperado de: https://www.datos.gov.co/Salud-y-Protecci-n-Social/Casos-positivos-de-COVID-19-en-Colombia/gt2j-8ykr/data [2020]
