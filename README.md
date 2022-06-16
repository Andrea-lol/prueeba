# BLUE PY - IDE ??

![version](https://img.shields.io/badge/version-1.0.0-blue.svg) 

![Image](https://github.com/Andrea-lol/prueeba/blob/main/img/Logo.png)

*Blue Py - IDE* es un proyecto que consiste en el desarrollo de un entorno integrado de desarrollo para el lenguaje de programaci¨®n python, desarrollado 
principalmente con prop¨®sitos educacionales para apoyar la ense?anza y el aprendizaje de la programaci¨®n orientada a objetos en el lenguaje de programaci¨®n 
Python. El cual permitir¨¢ mostrar gr¨¢ficamente la estructura de clases de una aplicaci¨®n en desarrollo,los objetos pueden ser creados y probados 
interactivamente,gracias a contar con una interfaz de usuario simple, esta facilidad de interacci¨®n permite experimentar de manera f¨¢cil con los objetos en 
desarrollo. Los conceptos de la programaci¨®n orientada a objetos (clases, objetos, comunicaci¨®n a trav¨¦s de llamadas a m¨¦todos). 


## Tabla de Contenido

* [Requerimientos](#requerimientos)
* [Objetivos](#objetivos)
* [Arquitectura](#arquitectura)
* [Herramientas Utilizadas](#herramientas-utilizadas)
* [Estructura del Proyecto](#estructura-del-proyecto)
* [Recursos](#recursos)
* [Autores](#autores)


## Requerimientos ??

_Este proyecto cuenta con los siguientes requerimientos:_

* RF-1: Maquetar los contenedores de cada uno de los componentes de la aplicaci¨®n.
* RF-2: Crear un nuevo proyecto.
* RF-3: Abrir un proyecto anterior.
* RF-4: Visualizar informaci¨®n acerca de la aplicaci¨®n.
* RF-5: Crear paquetes dentro del proyecto.
* RF-6: Eliminar paquetes dentro del proyecto.
* RF-7: Crear archivos Python.
* RF-8: Eliminar archivos Python.
* RF-9: Crear clases.
* RF-10: Eliminar clases.
* RF-11: Visualizar los paquetes, archivos y clases registradas.
* RF-12: Visualizar la relaci¨®n de herencia entre clases.
* RF-13: Modificar el contenido de un archivo Python.
* RF-14: Visualizar las instancias creadas.
* RF-15: Crear instancias de las clases.
* RF-16: Eliminar instancias de las clases.
* RF-17: Visualizar el detalle de cada instancia creada.
* RF-18: Visualizar la terminal de comandos.
* RF-19: Ingresar comandos en la terminal.
* RF-20: Limpiar la terminal de comandos.
* RF-21: Reiniciar la terminal de comandos.


## Objetivos ??

Los objetivos de Blue Py son:

- Objetivo General ??: Desarrollar un IDE para los estudiantes de primeros semestres del programa de Ingenier¨ªa de Sistemas de la UFPS el cual facilite 
el aprendizaje de la programaci¨®n orientada a objetos con Python. 

- Objetivos Espec¨ªficos ??: 
	1. _Determinar los requerimientos para el funcionamiento del IDE para la ense?anza de la programaci¨®n orientada a objetos con Python._
    2. _Definir la arquitectura del proyecto y los aspectos metodol¨®gicos del desarrollo del proyecto._
	3. _Desarrollar el IDE Blue Py._


## Arquitectura ??

![Image](https://github.com/Andrea-lol/prueeba/blob/main/img/arquitectura%20blue%20py.png)

La arquitectura seleccionada para el desarrollo de nuestro proyecto es la MVC II, en esta arquitectura el m¨®dulo Modelo proporciona toda la funcionalidad 
b¨¢sica y los datos compatibles con una base de datos. El m¨®dulo de vista muestra los datos mientras que el m¨®dulo de controlador toma solicitudes de entrada, 
valida los datos de entrada, inicia el modelo y la vista y su conexi¨®n, y distribuye tareas. El Controlador y la Vista se registran con el m¨®dulo Modelo. Cada 
vez que se modifican los datos en el m¨®dulo Modelo, se notifican los cambios al m¨®dulo Vista y al m¨®dulo Controlador. En la arquitectura MVC-II, el m¨®dulo View 
y el m¨®dulo Controller est¨¢n separados. Esto permite la divisi¨®n del trabajo. Adem¨¢s, debido a que la tecnolog¨ªa de la interfaz gr¨¢fica se actualiza 
r¨¢pidamente y los requisitos comerciales cambian muy a menudo, es mucho mejor mantener la vista separada del controlador.


## Herramientas Utilizadas ???
_Las herramientas utilizadas para el desarrollo del proyecto fueron:_

* [Java](https://www.java.com/es/) - Lenguaje de Programaci¨®n
* [Java Swing](https://www.java.com/es/) - Biblioteca Gr¨¢fica
* [Python](https://www.python.org) - Lenguaje de Programaci¨®n
* [Maven](https://maven.apache.org) - Herramienta de Software

<p align="center"><img src="https://cdn-icons-png.flaticon.com/512/226/226777.png" width="74" height="64" > <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Python-logo-notext.svg/768px-Python-logo-notext.svg.png" width="64" height="64" margin-right: 20px> <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/52/Apache_Maven_logo.svg/2560px-Apache_Maven_logo.svg.png" width="180" height="64"></p>



## Estructura del Proyecto ??	

Within the download you'll find the following directories and files:

```
material-dashboard
    ©À©¤©¤ assets
    ©¦?? ©À©¤©¤ css
    ©¦?? ©À©¤©¤ fonts
    ©¦?? ©À©¤©¤ img
    ©¦?? ©À©¤©¤ js
    ©¦?? ©¦?? ©À©¤©¤ core
    ©¦?? ©¦?? ©À©¤©¤ plugins
    ©¦?? ©¦?? ©¸©¤©¤ material-dashboard.js
    ©¦?? ©¦?? ©¸©¤©¤ material-dashboard.js.map
    ©¦?? ©¦?? ©¸©¤©¤ material-dashboard.min.js
    ©¦?? ©¸©¤©¤ scss
    ©¦??     ©À©¤©¤ material-dashboard
    ©¦??     ©¸©¤©¤ material-dashboard.scss
    ©À©¤©¤ docs
    ©¦?? ©À©¤©¤ documentation.html
    ©À©¤©¤ pages
    ©À©¤©¤ CHANGELOG.md
    ©À©¤©¤ gulpfile.js
    ©À©¤©¤ package.json
```




## Recursos ????

Para conocer m¨¢s a fondo sobre el proyecto se puede observar en el enlace [Blue Py](https://drive.google.com/drive/folders/1b5IwBA2nswt6BmnGF4TCFswfDyvEJSMG?usp=sharing)

- Demo: <https://demos.creative-tim.com/material-dashboard/pages/dashboard.html>
- Download Page: <https://www.creative-tim.com/product/material-dashboard>
- Documentation: <https://demos.creative-tim.com/material-dashboard/docs/2.1/getting-started/introduction.html>
- License Agreement: <https://www.creative-tim.com/license>
- PRO Version: <https://www.creative-tim.com/product/material-dashboard-pro>
- Support: <https://www.creative-tim.com/contact-us>
- Issues: [Github Issues Page](https://github.com/creativetimofficial/material-dashboard/issues)
- [Material Kit](https://www.creative-tim.com/product/material-kit?ref=github-md-free) - For Front End Development



## Autores ??

Los autores del proyecto son los estudiantes de la asignatura de arquitectura de software 2022-1 y la entidad educativa Universidad Francisco de 
Paula Santander.

Tambi¨¦n puedes mirar la lista de todos los [contribuyentes](https://github.com/Arquitectura-de-Software-UFPS-2022-I/python-poo-gui/graphs/contributors) quienes han participado en este proyecto. 

