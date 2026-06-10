
Documento de SOR – Diferencia entre derechos y permisos 

 

En los servidores o casi cualquier dispositivo electrónico con cierta capacidad de poder de procesamiento suelen existir distintos tipos de usuarios que tengan acceso, estos se diferencian por los nombres que poseen, pero también por los permisos y derechos que tienen, en este documento explicaremos la diferencia entre los permisos y los derechos de los usuarios para aprender a cuál tenemos que acceder o dar acceso. 

1.-¿Que es un derecho? 

R). - Son capacidades asignadas a un usuario o grupo que determinan que pueden hacer en un sistema operativos, además de no depender de un archivo o programa en concreto para poder ejecutarse, algunos ejemplos son: 

Derecho a iniciar sesión localmente 

Derecho a apagar el equipo 

Derecho a instalar software o controladores 

Derecho a cambiar la hora del sistema 

Derecho a crear cuentas de usuario 

 

En Windows, los derechos se gestionan desde Directiva de seguridad local → Asignación de derechos de usuario 

Los derechos de usuario se agrupan en tres grandes categorías: 

Acceso al sistema — controlan cómo y desde dónde puede entrar un usuario: de forma local, por red, como servicio, mediante tareas programadas, o directamente negársele el acceso. 

Gestión del sistema — permiten actuar sobre el propio sistema operativo: apagarlo, cambiar la hora, instalar controladores, gestionar copias de seguridad o depurar procesos. Casi todos estos están reservados a administradores. 

 

2.-¿Que es un privilegio? 

R). - Son controles de acceso sobre recursos específicos (archivos, carpetas, programas, claves de registro, etc.…), determinan que puede hacer un usuario específico sobre ese objeto en concreto. Algunos ejemplos sobre una carpeta son: 

Lectura → puede ver el contenido 

Escritura → puede crear o modificar archivos 

Ejecución → puede ejecutar programas dentro 

Control total → puede hacer todo, incluido cambiar los permisos del objeto 

En Windows se configuran con clic derecho - Propiedades - Seguridad. 

 

En Windows, los permisos se gestionan de forma gráfica y admiten tanto "Permitir" como "Denegar", siendo este último siempre el que prevalece, aunque haya un "Permitir" en otro grupo al que pertenezca el usuario. 

Seguridad y red — los más delicados: auditar eventos, tomar posesión de archivos de otros usuarios, apagar equipos remotamente o controlar la prioridad de procesos. Son los que más se explotan en ataques de escalada de privilegios.
