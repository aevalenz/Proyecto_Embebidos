
Biotec assistant

 *Sistema de monitoreo de signos vitales para pacientes que requieren de una observación constante*

Entre los documantos se encuentran 2 proteus
Uno con el atmega y el circuito y otro proteus con la raspberry
Se encuentran conectados mediante el compim con comunicacion serial

Se necesita ser complilados ambos y ser ejecutados al mismo tiempo.

Los valores medidos por los sensores son enviados a la raspberry que posteriormente
los sube a la nube (https://ubidots.com/stem/)
Dicha plataforma cuenta con la interfaz para que el doctor pueda observar en todo momento los signos vitales del paciente

nota: en caso de querer realizar su propia interfaz en ubidots, se requiere cambiar el Token y el API Label para realizar la conexion.
