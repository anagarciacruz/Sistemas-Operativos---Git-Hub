# Sistemas-Operativos---Git-Hub -- Ana Garcia Cruz
- Ana Garcia Cruz - Curso: ISI-S-NO-7-5

-	Crear un sistema de archivos de red con Amazon Elastic File System (EFS)
-	Paso 1: Crear un sistema de archivos en la consola de Amazon EFS.
-	En la consola de Amazon EFS, haga clic en Crear sistema de archivos.
-	Si la VPC predeterminada no está seleccionada en la lista desplegable de VPC, haga clic en la flecha de la lista desplegable y seleccione la VPC predeterminada. Acepte todos los valores predeterminados en Paso 1: configuración de acceso al sistema de archivos y haga clic en Paso siguiente.
-	-	Paso 2: Crear y configurar una máquina virtual con Amazon EC2
-	-	Creamos una máquina virtual
-	Escogemos una instancia. 
-	Agregamos una etiqueta. 
-	Configuramos el Grupo de seguridad. 
-	Revisamos la instancia. 
-	Creamos y descargamos un nuevo par de llaves.
-	Anote la dirección IP pública de la instancia de AWS, ya que la necesitará para conectar con la instancia en el apartado c del paso 4.
-Otorgue a su instancia acceso de red al sistema de archivos. Con la instancia seleccionada, seleccione Acciones > Redes > Cambiar grupos de seguridad.
Seleccione la casilla de verificación correspondiente al grupo de seguridad de VPC predeterminado y haga clic en Asignar grupos de seguridad.-
- Paso 3: Conectar la instancia.
- Paso 4: Montar la instancia.

 ¡Éxito!
Ha creado un sistema de archivos. Puede montar su sistema de archivos desde una instancia EC2 con un cliente NFSv4.1 instalado. También puede montar su sistema de archivos desde un servidor local a través de una conexión AWS Direct Connect.




