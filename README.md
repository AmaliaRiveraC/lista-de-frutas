##Página de tienda de frutas HTML
Crear archivo html en algún editor de código como ATOM o Sublime Tex. 
Agregar una etiqueta <img> a nuestro documento.
Crear una lista ordenada con la etiqueta <ol></ol> a la cual le asignaremos un id y a cada elemento de la lista lo identificarmeo con la etiqueta <li></li>


##Agregar un elemento a una lista ordenada: HTML-JavaScript
Crear dos etiquetas <input> debajo de nuestra lista. Un type="text" y el otro type="submit". NUestra etiqueta <input type="submit"> le agregaremos un onclick="".
Nuestro atributo onclick="return add_li()" será el encargado de llamar a la función add_li la cuál a su vez estará encargada de agregar un elemento a nuestra lista.
lo primero que declararemos dentro de nuestra función add_li() será una variable llamada var nuevo_li=document.getElementById()