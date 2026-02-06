# 💡 Mi reflexión sobre Filezilla Server

Después de darle caña a esta unidad, me he dado cuenta de que esto de pasar archivos no es solo mover carpetas y ya, sino que hay que tener mucho ojo con la seguridad y la red.

### Qué he aprendido
He aprendido a montar el servidor desde cero en mi Ubuntu. Lo que más se me ha quedado es que hoy en día no puedes ir por ahí sin seguridad; por eso, lo de configurar el **FTPS (FTP Seguro)** con los certificados y entender por qué el **Modo Pasivo** es el que manda para que el firewall no te de problemas, ha sido lo más importante.

### Qué no entiendo
A veces me rallo un poco con los permisos cuando un usuario está en varios grupos. Me gustaría tener más claro cuál es el permiso que gana cuando hay lío entre lo que dice el grupo y lo que dice el usuario. También me gustaría saber arreglar mejor los fallos esos raros de TLS cuando el cliente no se quiere conectar.

### Qué es lo que más me ha gustado y qué es lo que menos
* **Lo que más:** Ver que la **Integración Web** funciona de verdad. Me ha flipado subir mi `prueba.html` por FTP y ver que al segundo ya estaba publicada y la podía ver en el navegador con Apache. Ahí es donde ves cómo funcionan las webs de verdad.
* **Lo que menos:** Pelearme con los puertos y el modo activo. Es un poco tostón cuando el firewall te corta la conexión "sin avisar", aunque gracias a eso ahora entiendo por qué usamos el modo pasivo.

### Qué más me gustaría saber
Me molaría aprender sobre **SFTP**. Ya que hemos visto el FTPS, sé que en servidores Linux se usa mucho el SFTP porque solo usa un puerto (el 22) y tengo curiosidad por ver si es más fácil o difícil de configurar que lo que hemos hecho con Filezilla.
