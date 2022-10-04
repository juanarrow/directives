
# Directiva Atributo

## Explicación de la aplicación

Aplicación en ionic/agular que permite cambiar el color de fondo de un elemento del DOM

Al añadir el atributo appHihgLight al elemento del DOM este reacciona cambiando el color de fondo al pasar el ratón por encima del mismo
ej:
  \<p appHighLight\>Texto\</p\> #Por defecto el color de fondo es amarillo si no se indica
  
  \<p appHighLight="green"\>Texto\</p\> #Configura verde como color de fondo al pasar el ratón por encima
  
  \<p appHighLight="green" defaultColor="yellow"\>Texto\</p\> #Configura el color de fondo como verde
  
  \<p appHighLight defaultColor="yellow"\>Texto\</p\> #Al no configurar el color de HighLight se configura amarillo como color de fondo por defecto
  
  \<p defaultColor="yellow"\>Texto\</p\> #No hace nada puesto que no tiene aplicada la directiva appHighLight
  
  


## Cosas que aprenderás

@HostListener (<https://angular.io/api/core/HostListener>)

@Directive (<https://angular.io/guide/attribute-directives>)

creación de componentes <https://ionicframework.com/docs/cli/commands/generate>






