# peya-vero

#Instalacion
1. Abrir Navegador, ir a ''Extensiones''
2. Habilitar modo desarrollador
3. Agregar Extension sin empaquetar
4. Seleccionar carpeta #peya-vero

#Login
1. Crear PIN de 4 Digitos
2. Le pedira por siempre el PIN registrado
3. Aun no hay restablecimientos

#Software
1. Agregar nombre del sitio web, username, pass
2. Quedara registrado en "Cuentas Archivadas"
3. Botones habilitados y funcionales de ''Copiar'' y ''Eliminar''

#Cache
1. Guarda las cuentas al salir del navegador
2. Guarda el PIN registrado
3. Guarda si ''eliminas'' alguna cuenta.

#API - ''chrome.storage.sync''
es una herramienta proporcionada por Google Chrome para que las extensiones de Chrome puedan almacenar datos de manera persistente en el navegador. Es una forma útil de almacenar información como configuraciones, preferencias del usuario, tokens de autenticación y otros datos que necesitas mantener a través de las sesiones del navegador.

Algunos aspectos clave de la API chrome.storage.sync incluyen:

1. Persistencia: Los datos almacenados en chrome.storage.sync persisten en todas las sesiones del navegador. Esto significa que los datos estarán disponibles incluso después de cerrar y reiniciar el navegador.

2. Sincronización: La API se llama "sync" porque los datos almacenados se sincronizan automáticamente en todas las instancias del navegador Chrome del usuario, siempre que el usuario esté conectado a su cuenta de Google. Esto es útil si el usuario utiliza Chrome en varios dispositivos, ya que los datos estarán disponibles en todos ellos.

3. Capacidad de Almacenamiento: La API puede almacenar datos en forma de pares clave-valor. Los valores pueden ser cadenas de texto, objetos JSON o arreglos, lo que ofrece bastante flexibilidad en términos de tipos de datos.


4. API Asíncrona: La API chrome.storage.sync funciona de manera asíncrona, lo que significa que las operaciones de lectura y escritura no bloquearán la ejecución de otros procesos en tu extensión.

#Seguridad de API ''chrome.storage.sync''

1. Almacenamiento Seguro: Los datos almacenados en chrome.storage.sync se cifran antes de ser enviados y almacenados en los servidores de Google. Esto ayuda a proteger los datos contra el acceso no autorizado.

2. Sincronización Segura: La sincronización de datos entre las instancias del navegador está diseñada para ser segura. Los datos se cifran antes de ser enviados a través de la red y se descifran en el dispositivo del usuario.

3. Acceso Limitado: Solo la extensión que originó los datos puede acceder a ellos. Otras extensiones y sitios web no tienen acceso directo a los datos almacenados en chrome.storage.sync.

4. Cuentas de Google: Para acceder a los datos sincronizados, el usuario debe estar conectado a su cuenta de Google en el navegador. Esto añade una capa de seguridad adicional ya que el acceso a los datos está vinculado a la cuenta del usuario.

5. Actualizaciones de Seguridad: Google mantiene y actualiza regularmente Chrome y sus extensiones. Esto incluye parches de seguridad para abordar posibles vulnerabilidades. Mantener tanto el navegador como las extensiones actualizadas es crucial para mantener un entorno seguro.
