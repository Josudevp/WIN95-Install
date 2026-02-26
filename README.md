### Guia de instalación de Windows 95



> Para una instalación mas **grafica** puede observar el documento de WIN95-INSTALATION.docx



##### Herramientas:

1. Maquina virtual (No incluida en estos archivos)
2. Disco de inicio (Floppy/Diskette) que contiene MS-DOS 
3. ISO de Windows 95
4. FIX95



1. ##### Configuración de entorno y creación de maquina virtual Win95



Utilizaremos VirtualBox para emular el hardware necesario. Puedes descargar la versión estable en su sitio oficial.



###### **Creación de nueva maquina virtual**



Una vez dentro de la aplicación, presionamos en el icono azul a la esquina superior izquierda llamada "Nueva" y comenzaremos a llenar los datos:



**Datos a llenar dentro de la pestaña "New":**



**| Componente | Configuración Sugerida | Razón Técnica |**

**| :--- | :--- | :--- |**

**| RAM | 64 MB | Evita el error de "Memoria Insuficiente" en sistemas de 16/32 bits. |**

**| CPU | 1 Núcleo | Windows 95 no gestiona multiprocesamiento simétrico de forma nativa. |**

**| Disco Duro | 2 GB (VDI) | Límite máximo de direccionamiento para el sistema de archivos FAT16 ($2^{31}-1$ bytes). |**



##### 2\. Configuración de almacenamiento previo a instalación



Una vez creada la maquina virtual podemos configurar el almacenamiento para su instalación, para esto presionaremos click derecho en la maquina virtual creada y seleccionaremos Configuración o "Ctrl + S" -> 

Navegamos a la pestaña de Almacenamiento -> En la opción controlador Floppy haremos un click en la opción precreada "Vacio" -> A la derecha en los atributos hacemos click en el símbolo de disco color azul -> elegimos la opción de "Seleccionar/crear disquete virtual" -> Seleccionamos la opción añadir ubicada en la esquina superior izquierda -> Buscamos en nuestros archivos el archivo MS-DOS.img. Seleccionamos aceptar a todo y posteriormente iniciamos nuestra maquina virtual con Win95

