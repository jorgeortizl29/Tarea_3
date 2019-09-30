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
#en el caso de que ambos valores sean iguales, la secuencia arroja solo un numero, es decir, el numnero fijado. para este caso el numero 5.

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
##el insertar los condicionales visto en clases a la formula, ente caso la condicion par e impar a la listaDeNumeros, me permite conocer cuales de los valores de la lista son pares y cuales impares.

###EJERCICIO 9
##Para este caso el ganador es SI, ya que el total de votaciones para "Si" es mayor o igual al 30%.

###EJERCICIO 10
##El resultado generado de la suma anterior es igual a 7.
##El resultado de la resta es igual a -1.
#El resultado de la multiplicacion es igual a 12.
##El resultado de la division es igual a 0,75.

###EJERCICIO 11

##Diferencia Rectangulo
##La funcion arroja como resultado que la diferencia de las areas es 34 entre un rectangulo de base 10, altura 7 y uno de base 9 y altura 4.

##Diferencia Circulo
##La funcion arroja que si los valores de los radios 1 y 2 son 9 y 6 respectivamente. La diferencia del area de los cirvulos es de 141.3717.

###EJERCICIO ADICIONAL
##Las ventajas de las listas es que nos proporciona los datos de manera ordenada y facilita el manejo de ellos al momento de utilizarlos en diferentes formulas.Ademas entrega informacion relevante como por ejemplo si se quiesiera encontrar la posicion exacta de un valor en una larga lista de datos. Por otro lado el FOR-LOOP se destaca cuando se quiere dar una repeticion a cierta cantidad de datos siguiendo un parametro que haya sido asignado con anterioridad.



