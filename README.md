# Tarea_3
Guiaejercicio3
listaDeNumeros <- list(2,5,6,2,1,5,6,10,11,20,15)
listaDeNumeros[5]  
##EJERCICIO 1
listaDeNumeros[0]
##Al remplazar el valor 5 por un 0 no me arroja ningun valor, esto indica que no hay un valor asociado a esa posición.
listaDeNumeros[15]
##Al remplazar por un valor mayor a los elementos que estan en la lista, esta arroja "NULL" ya que la lista no posee esa cantidad de elementos.
listaDeNumeros[-7]
##Si remplazo el valor por un numero negativo, por ejemplo [-7] la plataforma me suprime el valor posicionado en el puesto 7.

##EJERCICIO 2
unlist(listaDeNumeros[5])
##Al usar unlist, solo se me entrega el valor correspondiente al numero seleccionado, pero no me entrega su posición.
#ejemplo
if(listaDeNumeros[5]+1>0){
  print("se cumple")
}
if(unlist(listaDeNumeros[5])+1>0){
  print("se cumple")
}  
##al trajar en modo list, me arroja un error, ya que no se pueden realizar operaciones con los numeros de la lista.
##al trabajar con el modo unlist si me permite trabajar con los numeros de la lista. 

##EJERCICIO 3
listaDeNumeros[5]<-12
##al insertsasr esta formula me cambia el valor ubicado en la posicion 5. (cambia el 1 por un 12)

##EJERCICIO 4
length(listaDeNumeros)
##la funcion length me entrega el largo o cantidad de datos de la lista.

##Pregunta 5
valorInicial <-5
valorFinal <-20
valorInicial <-20
valorFinal <-5

valorInicial : valorFinal

##Al aplicar un valor inicial (20) y final (5) me arroja una lista desde el valor incical seleccionado hasta el valor final seleccionado, es decir desde 20 hasta 5.
##Por el contrario cuando invierto los valores inicial y final, el listado que arroja tambien se invierte, es decir, desde 5 hasta 20.

valorInicial : length(listaDeNumeros)
##Al cambiar el valor final por length(listaDeNumeros) me arroja un listado desde el valor incial ya fijado hasta el numero total de datos de la lista, es decir, desde el 5 hasta el 11.

valorInicial <-5
valorFinal <-5

valorInicial : valorFinal
## en el caso de que ambos valores sean iguales, la secuencia arroja solo un numero, es decir, el numnero fijado. para este caso el numero 5.

##EJERCICIO 6
for (i in 1 : 100) {
  print(paste("cuento",i,"misisipis"))
}
##Al utilizar for se creo una nueva variable llamada "i" que me entrega la cantidad de valores seleccionados en la formula con el respectivo print, es decir, valores desde el cuento 1 misisipis al cuento 100 misisipis.

##EJERCICIO 7
for(i in (listaDeNumeros)){
  print(paste("cuento",i,"misisipis"))
}
##Al adaptar el codigo "i" anteriormente ejecutado que iban desde el 1 al 100  por la listaDeNumeros, me arroja los valores de la lista con su respectivo print, es decir, desde el "cuento 2 misisipis" (valor ubicado en la primera posicion de la lista) hasta el "cuento 15 misisipis" (valor uicado en la ultima posicion de la lista).

##EJERCICIO 8

