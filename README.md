# Lab07-ARSW

# Compile and run instructions

Para ejecutar el proyecto se debe realizar el sigueinte comando

* mvn srping-boot:run



# Primera parte 

Se agrego en la funcion publishPoint ennviar un objeto 

![](img/primeraparte1.png)

Se modifico connectAndSubscribe para que todos los que esten suscritos puedan ver los cambios realizados 

![](img/primeraparte2.png)

Para tener el sigueinte resultado, donde se crear en una pesatña un punto 

![](img/primeraparte3.png)

y en el otro se ve el mensaje de creado

![](img/primeraparte4.png)


# Segunda parte 

Con el fin de que realice el circulo apenas se realice la peticion se debe colocar de la sigueinte manera:

![](img/partedos1.png)

y ademas debemos cambiar la alerta por un callback 

![](img/partedos2.png)


dandonos como resultado:

primer punto en la primera pestaña  

![](img/partedos3.png)

replica en la otra pestaña

![](img/partedos4.png)

segundo punto en la pestaña 2

![](img/partedos5.png)

replica en la pestaña 1

![](img/partedos6.png)


# Tercera parte

Primero debemos adiccionar el nuevo campo

![](img/partetres0.png)

Y en init agregamos la inicalizacion de esta variable

![](img/partetres1.png)

Danadonos como resultado:
Primer dibujo en la primera pesatña inicializandose con 1

![](img/partetres2.png)

en la segunda pestaña inicializandose con 2 recibe los dibujos de 1

![](img/partetres3.png)

ahora realizamos un dibujo en 2 

![](img/partetres4.png)

y se realiza en 1

![](img/partetres5.png)


