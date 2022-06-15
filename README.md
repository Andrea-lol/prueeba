# BLUE PY - IDE 💻

![version](https://img.shields.io/badge/version-1.0.0-blue.svg) 

![Image](https://s3.amazonaws.com/creativetim_bucket/products/50/original/material-dashboard.jpg?1634648873)

*Blue Py - IDE* es un proyecto que consiste en el desarrollo de un entorno integrado de desarrollo para el lenguaje de programación python, desarrollado 
principalmente con propósitos educacionales para apoyar la enseñanza y el aprendizaje de la programación orientada a objetos en el lenguaje de programación 
Python. El cual permitirá mostrar gráficamente la estructura de clases de una aplicación en desarrollo,los objetos pueden ser creados y probados 
interactivamente,gracias a contar con una interfaz de usuario simple, esta facilidad de interacción permite experimentar de manera fácil con los objetos en 
desarrollo. Los conceptos de la programación orientada a objetos (clases, objetos, comunicación a través de llamadas a métodos). 


## Table of Contents

* [Requerimientos](#requerimientos)
* [Objetivos](#objetivos)
* [Arquitectura](#arquitectura)
* [Herramientas Utilizadas](#herramientas-utilizadas)
* [Estructura del Proyecto](#estructura-del-proyecto)
* [Recursos](#recursos)
* [Autores](#autores)


## Requerimientos

Este proyecto cuenta con los siguientes requerimientos:

* **RF-1: Maquetar los contenedores de cada uno de los componentes de la aplicación.**
* **RF-2: Crear un nuevo proyecto.**
* **RF-3: Abrir un proyecto anterior.**
* **RF-4: Visualizar información acerca de la aplicación.**
* **RF-5: Crear paquetes dentro del proyecto.**
* **RF-6: Eliminar paquetes dentro del proyecto.**
* **RF-7: Crear archivos Python.**
* **RF-8: Eliminar archivos Python.**
* **RF-9: Crear clases.**
* **RF-10: Eliminar clases.**
* **RF-11: Visualizar los paquetes, archivos y clases registradas.**
* **RF-12: Visualizar la relación de herencia entre clases.**
* **RF-13: Modificar el contenido de un archivo Python.**
* **RF-14: Visualizar las instancias creadas.**
* **RF-15: Crear instancias de las clases.**
* **RF-16: Eliminar instancias de las clases.**
* **RF-17: Visualizar el detalle de cada instancia creada.**
* **RF-18: Visualizar la terminal de comandos.**
* **RF-19: Ingresar comandos en la terminal.**
* **RF-20: Limpiar la terminal de comandos.**
* **RF-21: Reiniciar la terminal de comandos.**


## Objetivos

Los objetivos de Blue Py son:

- Objetivo General 💯: Desarrollar un IDE para los estudiantes de primeros semestres del programa de Ingeniería de Sistemas de la UFPS el cual facilite 
el aprendizaje de la programación orientada a objetos con Python. 

- Objetivos Específicos 🎯: 
	1. _Determinar los requerimientos para el funcionamiento del IDE para la enseñanza de la programación orientada a objetos con Python._
    2. _Definir la arquitectura del proyecto y los aspectos metodológicos del desarrollo del proyecto._
	3. _Desarrollar el IDE Blue Py._


## Arquitectura 📝

![Image](https://s3.amazonaws.com/creativetim_bucket/products/50/original/material-dashboard.jpg?1634648873)

La arquitectura seleccionada para el desarrollo de nuestro proyecto es la MVC II, en esta arquitectura el módulo Modelo proporciona toda la funcionalidad 
básica y los datos compatibles con una base de datos. El módulo de vista muestra los datos mientras que el módulo de controlador toma solicitudes de entrada, 
valida los datos de entrada, inicia el modelo y la vista y su conexión, y distribuye tareas. El Controlador y la Vista se registran con el módulo Modelo.Cada 
vez que se modifican los datos en el módulo Modelo, se notifican los cambios al módulo Vista y al módulo Controlador.En la arquitectura MVC-II, el módulo View 
y el módulo Controller están separados. Esto permite la división del trabajo. Además, debido a que la tecnología de la interfaz gráfica se actualiza 
rápidamente y los requisitos comerciales cambian muy a menudo, es mucho mejor mantener la vista separada del controlador.


## Herramientas Utilizadas 🛠️

_Las herramientas utilizadas para el desarrollo del proyecto fueron:_

* [Java](https://netbeans.apache.org) - IDE utilizado
* [Java Swing](https://www.apachefriends.org/es/index.html) -Paquete de software libre
* [Python](https://netbeans.apache.org) - IDE utilizado
* [Maven](https://www.apachefriends.org/es/index.html) -Paquete de software libre

<img src="https://cdn-icons-png.flaticon.com/512/226/226777.png" width="64" height="64"> <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Python-logo-notext.svg/768px-Python-logo-notext.svg.png" width="64" height="64"> <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/52/Apache_Maven_logo.svg/2560px-Apache_Maven_logo.svg.png" width="85" height="64"> 



## Estructura del Proyecto
Within the download you'll find the following directories and files:

```
material-dashboard
    ├── assets
    │   ├── css
    │   ├── fonts
    │   ├── img
    │   ├── js
    │   │   ├── core
    │   │   ├── plugins
    │   │   └── material-dashboard.js
    │   │   └── material-dashboard.js.map
    │   │   └── material-dashboard.min.js
    │   └── scss
    │       ├── material-dashboard
    │       └── material-dashboard.scss
    ├── docs
    │   ├── documentation.html
    ├── pages
    ├── CHANGELOG.md
    ├── gulpfile.js
    ├── package.json
```



## Recursos 📑
- Demo: <https://demos.creative-tim.com/material-dashboard/pages/dashboard.html>
- Download Page: <https://www.creative-tim.com/product/material-dashboard>
- Documentation: <https://demos.creative-tim.com/material-dashboard/docs/2.1/getting-started/introduction.html>
- License Agreement: <https://www.creative-tim.com/license>
- PRO Version: <https://www.creative-tim.com/product/material-dashboard-pro>
- Support: <https://www.creative-tim.com/contact-us>
- Issues: [Github Issues Page](https://github.com/creativetimofficial/material-dashboard/issues)
- [Material Kit](https://www.creative-tim.com/product/material-kit?ref=github-md-free) - For Front End Development



## Autores ✒️

Los autores del proyecto son los estudiantes de la asignatura de arquitectura de software 2022-1 y la entidad educativa Universidad Francisco de 
Paula Santander.

También puedes mirar la lista de todos los [contribuyentes](https://github.com/Arquitectura-de-Software-UFPS-2022-I/python-poo-gui/graphs/contributors) quiénes han participado en este proyecto. 

