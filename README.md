# learn-javascript
Programas de practica de JavaScript

http://www.w3schools.com/js/js_arithmetic.asp


>> Cambiar contenido HTML

document.getElementById("demo").innerHTML = "Hola JavaScript"
	* getElemntById("demo")  Encontrar un elemento HTML con id=demo
	* innerHTML  Cambiar el contenido del elemento HTML


>> Cambiar atributo HTML

document.getElementById('myImage').src='imagen.gif'
	* scr='imagen1.gif'  Cambiamos la imagen del elemento con id=myImage


>> Cambiar el estilo HTML (CSS)

document.getElementById("demo").style.fontSize = "35px"
	* style.fontsize = "35px"  Cambiamos el tamaño de la letra


>> Ocultar elementos HTML

document.getElementById("demo").style.display='none'
	* style.display='none'  Ocultamos el elemento con id=demo


>> Mostrar elementos HTML

document.getElementById("demo").style.display="block"
	* style.display="block"  Mostramos el elemento con id=demo


>> Donde colocar el codigo JavaScript
	<script> codigo JavaScript </script>
	Puede colocarse en las secciones Body o Head de una pagina HTML. 

>> Archivo JavaScript aparte 
	<script> src="myScript.js" </script>


JavaScript OUTPUT
	window.alert(5 + 6)   Cuadre de alerta
	document.write(5 + 6)      Muestra texto en documento (Solo para pruebas)
	document.getElementById("demo").innerHTML = 5 + 6 
        console.log(5 + 6)       Presinar F12 y seleccionar consola

JAVASCRIPT SINTAX

Declaring (Creating) JavaScript Variables
	* var person = "John Doe",
	  carName = "Volvo",
	  price = 200;


JavaScript Type Operators
	* typeof   Retorna el tipo de Variable
	* instanceof    Retorna true si un objeto es una instancia de un tipo de objeto
