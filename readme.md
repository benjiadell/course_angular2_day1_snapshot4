Angular 2: Getting Started - SnapShot 4
===================
En esta parte veremos estos contenidos del curso de Pluralshight:

 - More on Components

More on Components
-------------------

En esta seccion se hablará de como mejorar los componentes meiantes tecnicas como estas:

![enter image description here](https://i.imgur.com/BhdivyV.png)

### String typing & interfaces
Utilizaremos interfaces para especificar que propiedades tiene que contener un producto. De este modo evitaremos problemas a la hora de establecer u obtener valores.

#### Encapsuling styles
El objetio es tener uno o varios CSS para cada componente
#### Lifecycle hooks
Aprenderemos el uso de eventos asociados al ciclo de vda del componente, en concreto, el uso de *OnInit*
#### Custom pipes
Usaremos custom Pipes para filtar la lista de procductos en funcion del valor establecido en el filtro.
#### Relative paths with ModuleId
Los módulos pueden ser referenciados por su ModuloId. Para ello debemos usar un cargador de componentes como SystemJS. Es el que se utiiza para este ejemplo.


Para ello clonamos el **SnapShot 4** desde le primer commit:

    git clone https://github.com/tc-frontend/course_angular2_day1_snapshot4
    cd course_angular2_day1_snapshot4
    git checkout tag/init
    npm install
    code .
 
Seguimos los pasos detallados en el historial de commits:

    https://github.com/tc-frontend/tc-frontend-angular2_day1_snapshot4/commits/master   
  
Si queremos ver la App en nuestro browser

    npm start

Si queremos ver la solucion final de este SnapShot:

    git checkout master
    npm install
    npm start

