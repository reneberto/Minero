# Minero
A minar con Docker

Obtener una dirección valida (Wallet)

Las direcciones de la Red Chaucha se obtienen utilizando la Chauchera, que es un software que te permite enviar y recibir Chauchas desde tu computadora. Este software esta disponible en la página web oficial del Proyecto Chaucha, en la sección de Descargas.

Al descargar la chauchera y ejecutarla por primera vez, esta comenzara a descargar toda la cadena de transacciones que hay hasta ese momento.

Mientras se sincroniza tu chauchera puedes ir al menu superior y ver la opcion Recibir, en donde verás un codigo (en la seccion dirección) que es tu billetera virtual o wallet, con ese codigo podras minar chauchas, es basicamente una direccion a donde irán tus chauchas minadas.


Luego clonar proyecto y construir 

docker run mkell43/minerd -a scrypt -o stratum+tcp://artesa.chaucha.cl:3008 -u usuario.worker -p ClaveDelWorker
