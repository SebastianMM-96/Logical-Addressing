# Direccionamiento lógico

Las primeras dos capas del modelo OSI o TCP/IP, resuelven la comunicación entre dos o más dispositivos
conectados al mismo medio de comunicación. Sin embargo, en ocasiones pueden surgir algunos problemas,
por ejemplo:

a) Las redes pueden llegar a ser muy grandes, lo que hace muy complicada su administración.

b) Los nodos, dispositivos o computadoras, pueden estar separados por grandes distancias, lo que hace
poco practico mantener un mismo medio de transmisión. ¿Qué sucede con el espacio libre, es decir, las
comunicaciones inalámbricas?

***

Una posible solución es tener redes “pequeñas” conectadas entre ellas, y permitir que estas “redes pequeñas”
(subredes) puedan comunicarse, formando una especie de red de redes.1 Esta solución sin embargo, lleva a
resolver un conjunto de nuevos problemas, algunos ellos tendrá que resolver en la presente práctica. Estos
problemas son:

a) La dirección física sólo es válida para aquellos dispositivos conectados al mismo medio de transmisión,
dado que ahora hay más de dos subredes en diferentes medios de transmisión, será necesario un
nuevo espacio de direcciones, que permita llevar un paquete de una subred a otra. Este nuevo espacio
de direcciones, que llamaremos direcciones lógicas, esta asociado a cada subred e identifica de manera
única, a cada máquina perteneciente a la subred.

b) ¿Quién es el nodo encargado de llevar el paquete de una subred a otra? Este nodo en ocasiones se le
conoce con el nombre de puente (gateway). El nodo puente por lo tanto, deberá estar conectado a las
dos subredes.

c) En el caso de que el paquete de datos tenga que viajar entre más una subred, ¿cuál será el mejor de los
caminos? ¿El mejor camino se basará en tiempo, distancia o alguna otra métrica? ¿Quién será el
encargado de “medir” o establecer esos caminos? ¿Los caminos serán fijos o pueden cambiar en el
tiempo?
