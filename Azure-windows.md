Primero has de crear una maquina virtual windows azure, a traves de su sitio web
<img width="1364" height="639" alt="image" src="https://github.com/user-attachments/assets/e03ee4ea-a165-4044-abf5-a26c6cd30e06" />

2.- debes poner informacion como que sistam operativo, tamaño, región, direccion ip, contraseña de accesos y otra info para poder generar la maquina virtual, después dar todos los detalles de
la maquina virtual, esta no funcionara si no pones la región correcta,

después has de descargar un archivo terminado en rdp al seleccionar la opción de conectar y a traves de ese podras tener acceso a la maquina virtual
te abrira una venta similar a esta:
<img width="566" height="450" alt="image" src="https://github.com/user-attachments/assets/3ec3e84b-69c7-4b63-b733-8633998364c3" />
haz de sellecionar todas la casillas y introducir la contraseña que metiste antes para acceder a tu maquina virtual.

)Desde el sitio web se pueden modificar cosas como el tamaño de la pantalla u ptras cosas del servidor, tambien se pueden agregar discos, estos hay que darles nombre y tamaño
desde el sitio web)
<img width="804" height="618" alt="disocdod" src="https://github.com/user-attachments/assets/3ca5292d-74e5-4bbf-979d-0c473118a156" />

Finalmente se pueden crear redes y grupos de seguridad en este tipo de servidores, al instalar servicios como ftp y active directory domains and services, estos ya deje claros 
como configurarlos en otro  tutorial asi que no lo haré aquí
Para agregar reglas de redes se tiene que acceder a firewal y escogre el apartado a la izquierda que pone reglas de entrada, click derecho ,nuevo y te mostrara esto:
<img width="796" height="592" alt="Captura de pantalla 2026-06-03 014344" src="https://github.com/user-attachments/assets/882dd216-5ec9-4218-809c-872d8133d124" />
yo creare una que afecta los puertos 20 y 21 asi que esocgo las opciones de la imagen y despues de otras opciones que se dejan en predeterminado, se crea la regla
<img width="791" height="601" alt="Captura de pantalla 2026-06-03 014439" src="https://github.com/user-attachments/assets/78675c03-de0c-4354-867e-808d21fb8607" />


Cuando estos están instalados se accedes a traves de la pestaña de herramientas a active directory groups and users si se desea crear un grupo de seguridad, se seleciona 
acción o click derecho, nuevo, grupo, se le pone un nombre y se denomina como grupo de seguridad, se pone crear y listo.
<img width="811" height="573" alt="Captura de pantalla 2026-06-03 013934" src="https://github.com/user-attachments/assets/9800d55e-0b66-4a15-8ace-a18ee479bc00" />
<img width="811" height="573" alt="sistemasoperativos-gruposecutirioa" src="https://github.com/user-attachments/assets/23264b8d-503a-448b-b5ea-113cf7094ff5" />
<img width="1364" height="639" alt="Captura de pantalla 2026-06-03 014757" src="https://github.com/user-attachments/assets/21d5e54e-30ac-49d7-af06-f38213821bd7" />



