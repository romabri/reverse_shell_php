# Descripción:
El script permite establecer una conexión TCP saliente hacia una dirección IP y puerto predefinidos. Una vez establecida la conexión, el atacante obtiene una shell remota en el sistema comprometido, ejecutada como el usuario actual del servidor web (generalmente "apache").

## Limitaciones:
 Requiere PHP versión 4.3+ o 5+.
 El uso de algunas funciones como proc_open y stream_set_blocking puede estar restringido en ciertos entornos o sistemas operativos.
 La demonización del proceso PHP para evitar la creación de "zombies" puede no ser posible en todos los casos.
 Algunas opciones de compilación pueden ser necesarias para la demonización, pero raramente están disponibles.

## Uso:
El script se ejecuta en el sistema comprometido, y una vez que se establece la conexión inversa, el atacante puede enviar comandos al sistema y recibir la salida de estos comandos.

## Licencia:
El script está licenciado bajo la GNU General Public License versión 2, lo que significa que es software libre y puede ser redistribuido y modificado bajo ciertas condiciones.

## Aviso legal:
El uso de esta herramienta está destinado únicamente para fines legales. Los usuarios asumen la plena responsabilidad de cualquier acción realizada utilizando este script. El autor no acepta responsabilidad por daños causados por su uso.
