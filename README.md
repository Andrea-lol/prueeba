# BLUE PY - IDE 馃捇

![version](https://img.shields.io/badge/version-1.0.0-blue.svg) 

![Image](https://github.com/Andrea-lol/prueeba/blob/main/img/Logo.png)

*Blue Py - IDE* es un proyecto que consiste en el desarrollo de un entorno integrado de desarrollo para el lenguaje de programaci贸n python, desarrollado 
principalmente con prop贸sitos educacionales para apoyar la ense帽anza y el aprendizaje de la programaci贸n orientada a objetos en el lenguaje de programaci贸n 
Python. El cual permitir谩 mostrar gr谩ficamente la estructura de clases de una aplicaci贸n en desarrollo,los objetos pueden ser creados y probados 
interactivamente,gracias a contar con una interfaz de usuario simple, esta facilidad de interacci贸n permite experimentar de manera f谩cil con los objetos en 
desarrollo. Los conceptos de la programaci贸n orientada a objetos (clases, objetos, comunicaci贸n a trav茅s de llamadas a m茅todos). 


## Table of Contents

* [Requerimientos](#requerimientos)
* [Objetivos](#objetivos)
* [Arquitectura](#arquitectura)
* [Herramientas Utilizadas](#herramientas-utilizadas)
* [Estructura del Proyecto](#estructura-del-proyecto)
* [Recursos](#recursos)
* [Autores](#autores)


## Requerimientos

_Este proyecto cuenta con los siguientes requerimientos:_

* RF-1: Maquetar los contenedores de cada uno de los componentes de la aplicaci贸n.
* RF-2: Crear un nuevo proyecto.
* RF-3: Abrir un proyecto anterior.
* RF-4: Visualizar informaci贸n acerca de la aplicaci贸n.
* RF-5: Crear paquetes dentro del proyecto.
* RF-6: Eliminar paquetes dentro del proyecto.
* RF-7: Crear archivos Python.
* RF-8: Eliminar archivos Python.
* RF-9: Crear clases.
* RF-10: Eliminar clases.
* RF-11: Visualizar los paquetes, archivos y clases registradas.
* RF-12: Visualizar la relaci贸n de herencia entre clases.
* RF-13: Modificar el contenido de un archivo Python.
* RF-14: Visualizar las instancias creadas.
* RF-15: Crear instancias de las clases.
* RF-16: Eliminar instancias de las clases.
* RF-17: Visualizar el detalle de cada instancia creada.
* RF-18: Visualizar la terminal de comandos.
* RF-19: Ingresar comandos en la terminal.
* RF-20: Limpiar la terminal de comandos.
* RF-21: Reiniciar la terminal de comandos.


## Objetivos

Los objetivos de Blue Py son:

- Objetivo General 馃挴: Desarrollar un IDE para los estudiantes de primeros semestres del programa de Ingenier铆a de Sistemas de la UFPS el cual facilite 
el aprendizaje de la programaci贸n orientada a objetos con Python. 

- Objetivos Espec铆ficos 馃幆: 
	1. _Determinar los requerimientos para el funcionamiento del IDE para la ense帽anza de la programaci贸n orientada a objetos con Python._
    2. _Definir la arquitectura del proyecto y los aspectos metodol贸gicos del desarrollo del proyecto._
	3. _Desarrollar el IDE Blue Py._


## Arquitectura 馃摑

![Image](https://github.com/Andrea-lol/prueeba/blob/main/img/arquitectura%20blue%20py.png)

La arquitectura seleccionada para el desarrollo de nuestro proyecto es la MVC II, en esta arquitectura el m贸dulo Modelo proporciona toda la funcionalidad 
b谩sica y los datos compatibles con una base de datos. El m贸dulo de vista muestra los datos mientras que el m贸dulo de controlador toma solicitudes de entrada, 
valida los datos de entrada, inicia el modelo y la vista y su conexi贸n, y distribuye tareas. El Controlador y la Vista se registran con el m贸dulo Modelo.Cada 
vez que se modifican los datos en el m贸dulo Modelo, se notifican los cambios al m贸dulo Vista y al m贸dulo Controlador.En la arquitectura MVC-II, el m贸dulo View 
y el m贸dulo Controller est谩n separados. Esto permite la divisi贸n del trabajo. Adem谩s, debido a que la tecnolog铆a de la interfaz gr谩fica se actualiza 
r谩pidamente y los requisitos comerciales cambian muy a menudo, es mucho mejor mantener la vista separada del controlador.


## Herramientas Utilizadas 馃洜锔?
_Las herramientas utilizadas para el desarrollo del proyecto fueron:_

* [Java](https://www.java.com/es/) - Lenguaje de Programaci贸n
* [Java Swing](https://www.java.com/es/) - Biblioteca Gr谩fica
* [Python](https://www.python.org) - Lenguaje de Programaci贸n
* [Maven](https://maven.apache.org) - Herramienta de Software

<p align="center"><img src="https://cdn-icons-png.flaticon.com/512/226/226777.png" width="74" height="64" > <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Python-logo-notext.svg/768px-Python-logo-notext.svg.png" width="64" height="64" margin-right: 20px> <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/52/Apache_Maven_logo.svg/2560px-Apache_Maven_logo.svg.png" width="180" height="64"></p>



## Estructura del Proyecto
Within the download you'll find the following directories and files:

```
material-dashboard
    鈹溾攢鈹� assets
    鈹偮犅?鈹溾攢鈹� css
    鈹偮犅?鈹溾攢鈹� fonts
    鈹偮犅?鈹溾攢鈹� img
    鈹偮犅?鈹溾攢鈹� js
    鈹偮犅?鈹偮犅?鈹溾攢鈹� core
    鈹偮犅?鈹偮犅?鈹溾攢鈹� plugins
    鈹偮犅?鈹偮犅?鈹斺攢鈹� material-dashboard.js
    鈹偮犅?鈹偮犅?鈹斺攢鈹� material-dashboard.js.map
    鈹偮犅?鈹偮犅?鈹斺攢鈹� material-dashboard.min.js
    鈹偮犅?鈹斺攢鈹� scss
    鈹偮犅?    鈹溾攢鈹� material-dashboard
    鈹偮犅?    鈹斺攢鈹� material-dashboard.scss
    鈹溾攢鈹� docs
    鈹偮犅?鈹溾攢鈹� documentation.html
    鈹溾攢鈹� pages
    鈹溾攢鈹� CHANGELOG.md
    鈹溾攢鈹� gulpfile.js
    鈹溾攢鈹� package.json
```



## Recursos 馃搼

Para conocer m谩s a fondo sobre el proyecto se puede observar en el enlace [Blue Py](https://drive.google.com/drive/folders/1b5IwBA2nswt6BmnGF4TCFswfDyvEJSMG?usp=sharing)

- Demo: <https://demos.creative-tim.com/material-dashboard/pages/dashboard.html>
- Download Page: <https://www.creative-tim.com/product/material-dashboard>
- Documentation: <https://demos.creative-tim.com/material-dashboard/docs/2.1/getting-started/introduction.html>
- License Agreement: <https://www.creative-tim.com/license>
- PRO Version: <https://www.creative-tim.com/product/material-dashboard-pro>
- Support: <https://www.creative-tim.com/contact-us>
- Issues: [Github Issues Page](https://github.com/creativetimofficial/material-dashboard/issues)
- [Material Kit](https://www.creative-tim.com/product/material-kit?ref=github-md-free) - For Front End Development



## Autores 鉁掞笍

Los autores del proyecto son los estudiantes de la asignatura de arquitectura de software 2022-1 y la entidad educativa Universidad Francisco de 
Paula Santander.

Tambi茅n puedes mirar la lista de todos los [contribuyentes](https://github.com/Arquitectura-de-Software-UFPS-2022-I/python-poo-gui/graphs/contributors) qui茅nes han participado en este proyecto. 

