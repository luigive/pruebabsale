# pruebabsale
DOCUMENTACION prueba bsale

Creación de archivo index.html, el cual debe recibir los datos de la api creada y mostrar la interfaz según lo solicitado. 

 

*descargar e importar el css y el js necesario para utilizar bootstrap (el bootstrap.min.css) y el (bootstrap.min.js)  

 

*crear cabecera con un icono, el buscador html con id products, y el boton de búsqueda 

 

*crear contenedor el cual tendrá los filtros de precio y categorías , un div con id ”rowprincipal” el cual tendrá la información de los productos y un div con id paginador el cual tendrá el paginado. 

 

*crear función  Getdata, la cual recibirá como parámetro un type(este argumento sera para distinguir entre buscar las categorías y los productos), esta debe hacer un fetch al api y rescatar los datos y devolverlos. 

 

*crear función categoryselect la cual debe ejecutar la función getdata el json de categorías, y rellenar el select con las categorías obtenidas con un foreach 

 

*crear función builddata la cual debe ejecutar la función getdata para obtener los productos y hacer un foreach, dentro de este foreach debe verifica si el producto tiene descuentos, en caso de que tener debe armar la interfaz según tenga o no descuentos, también debe verificar si no viene url de la imagen del producto colocar una imagen por defecto , luego armar la interfaz principal y el paginador. 

 

*crear funcion filterdata, esta debe rescatar tanto los filtros del select, y el buscador de productos y ejecutar la funcion builddata pasandole como argumento un arreglo con todos los datos. 

 

*crear funcion windows.onload , y ejecutar la funcion categoryselect() y vuildata para armar la interfaz al momento de cargar la pagina 

 
