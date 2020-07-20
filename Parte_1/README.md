# Parte 1

Con ayuda de tres máquinas virtuales, simule el enlace entre dos subredes, para ello:

a) Una máquina llamada A, enviará un mensaje a una máquina llamada B. Entre A y B no hay un enlace
directo, por lo que la comunicación tendrá que pasar por medio de una maquina llamada G.

b) La máquina G hará el papel de gateway, todo paquete cuyo destino sea la máquina A o B, lo pasará a la
máquina respectiva. Es este caso, es importante hacer notar que, la máquina A no conoce la dirección
física de B, solo su dirección lógica que usted tendrá que definir; de la misma forma, la máquina B no
conoce la dirección física de A, solo su dirección lógica.

c) Las máquinas A y B, conocen la dirección física de G, dado que estamos suponiendo que están
conectadas a las respectivas subredes. Por lo tanto, la máquina G conoce las direcciones físicas de A y
B.
