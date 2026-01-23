# enlaces_UD5

## Ejercicio1
[Introducción y arquitectura de Filezilla Server](https://github.com/JosecarlosGlr/Introducci-nYArquitecturaFilezilla)  

Diagrama de ciclo de vida de una sesión FTP, identificando el uso del puerto 21 para el control y la apertura dinámica de canales de datos, además comparo un esquema activo con uno pasivo y pequeña tabla con sus diferencias.

## Ejercicioi2
[Instalación y configuración inical de servidor](https://github.com/JosecarlosGlr/Instalaci-nYConfiguraci-nInicialDeServidor)

Instalo FileZilla Server, configurando la escucha en el puerto 21 y habilitando su inicio automático en el sistema.

## Ejercicio3
[Creación de usuarios y grupos](https://github.com/JosecarlosGlr/CrecionDeUsuarioYGrupos)  

Creo el grupo grupo1 con permisos de lectura, escritura y borrado sobre el directorio raíz, añadiendo posteriormente dos usuarios (usuario1 y usuario2) que heredan dicha configuración automáticamente.

## Ejercicio4
[Configuración de acceso anónimo](https://github.com/JosecarlosGlr/ConfiguracionDeAccesoAnonimo)

Configuré el acceso anónimo creando el usuario anonymous sin contraseña, limitando sus permisos únicamente a lectura sobre el directorio raíz y verificando la conexión exitosa desde un cliente FTP

## Ejercicio5

[Pruebas en modo pasivo y activo](https://github.com/JosecarlosGlr/PruebasEnModoActivoYPasivo)

Configuro el rango de puertos pasivos (50000-50100) en el servidor y realizo pruebas de conexión forzando los modos Activo y Pasivo desde el cliente para comparar su funcionamiento

## Ejercicio6

[Pruebas con clientes en línea de comandos](https://github.com/JosecarlosGlr/PruebasConClientesEnL-neaDeComandos)

Realicé la conexión mediante el cliente lftp para soportar el cifrado TLS ignorando el certificado local, y ejecuté con éxito las operaciones de listar, subir y descargar archivos en el servidor.

## Ejercicio7

[Pruebas con clientes gráficos](https://github.com/JosecarlosGlr/PruebasConClientesGr-ficos)

Configuré una conexión persistente en FileZilla Client con cifrado TLS explícito y realicé transferencias bidireccionales de archivos, verificando el éxito de las operaciones en el registro de estado.

## Ejercicio8

[Configuración de FTP seguro (FTPS)](https://github.com/JosecarlosGlr/Configuraci-nDeFTPseguro-FTPS-)

Generé un certificado X.509 autofirmado en el servidor y configuré la política de usuario para exigir TLS estricto, verificando posteriormente el cifrado activo en el cliente.

## Ejercicio9

[Uso del navegador como cliente FTP](https://github.com/JosecarlosGlr/UsoDelNavegadorComoClienteFTP)

Intenté acceder al servidor FTP mediante un navegador web, confirmando que el soporte nativo es obsoleto (redirige a aplicaciones externas) y que carece de las funciones de seguridad (FTPS) y escritura (subida) que ofrece un cliente dedicado.
