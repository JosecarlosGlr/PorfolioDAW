# Reflexión sobre la unidad

En estas prácticas de **Tomcat** he consolidado mis conocimientos sobre servidores de aplicaciones Java. Lo que más me ha gustado ha sido la parte de **Docker**, ya que me sorprendió lo rápido que se puede levantar un servidor con un solo comando en comparación con la instalación manual. También me pareció muy interesante configurar el **Proxy Inverso con Apache**, ya que ahora entiendo cómo funcionan las webs reales que no muestran puertos raros en la URL.

Lo que más me costó fue la gestión de rutas en Linux. Al principio tuve problemas porque mi instalación de Tomcat estaba en `/opt` y no funcionaba como servicio automático (`systemctl`), lo que me obligó a investigar dónde estaban los scripts de arranque manuales. También tuve dificultades configurando el **HTTPS**, ya que un error de sintaxis en el archivo XML hacía que el servidor no arrancara, pero aprendí a leer los logs para solucionarlo.

He aprendido la importancia de los archivos de configuración (`server.xml` y `tomcat-users.xml`) y cómo un pequeño ajuste en los hilos (`maxThreads`) puede cambiar el rendimiento. Me quedo con la duda de cómo automatizar todo esto para no tener que editar archivos a mano cada vez.
