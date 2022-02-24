# Instalación y configuración

1) Instalar JDK 11 en su versión más reciente entrando a la página https://www.oracle.com/java/  
2) Instalar y configurar IntelliJ IDEA desde la página Instalar y configurar IntelliJ IDEA. 
3) Instalar y configurar el sistema de control de versiones Git.
4) Crear una cuenta en GitHub como usuario normal o estudiante (https://education.github.com/) con tu cuenta de correo. 
5) Crear un repositorio en el servicio de repositorios en línea.

# Uso del programa
El programa desarrollado contará con las siguientes funciones:

1) Dar de alta doctores: se deberán poder dar de alta los doctores del consultorio médico, los datos básicos serán:
• Identificador único.
• Nombre completo.
• Especialidad.

2) Dar de alta pacientes: se deberán poder registrar los pacientes que acudan al consultorio médico, los datos
básicos serán:
• Identificador único.
• Nombre completo.

3) Crear una cita con fecha y hora: se deberán poder crear múltiples citas, los datos básicos serán:
• Identificador único.
• Fecha y hora de la cita.
• Motivo de la cita.

4) Relacionar una cita con un doctor y un paciente: cada una de las citas creadas deberá estar relacionada con un
doctor y un paciente.
• Tener control de acceso mediante administradores: solo ciertos usuarios podrán acceder al sistema mediante un
identificador y una contraseña.
• Toda la información deberá ser almacenada en archivos de texto plano con formato CSV, o en su defecto utilizar
algún formato más avanzado como JSON o XML. 

La aplicación será totalmente portable, es decir, que se podrá ejecutar en cualquier sistema operativo que tenga instalado
Java, para ello deberá ser configurada para compilarse como un archivo tipo FAT JAR y garantizar que todas las
dependencias estarán incluidas

La aplicación contará con el manejo correcto de recursos y excepciones, es decir, si ocurre una excepción, el programa no
saldrá, sino que seguirá ejecutándose y mostrará el mensaje de error en la pantalla.

Créditos: Este programa se desarrolla con fines académicos en la Universidad Tecmilenio para la materia Computación en Java, en la carrera Ingeniería en Desarrollo de Software.
