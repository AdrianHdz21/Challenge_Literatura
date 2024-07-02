# Challenge Literatura:
  Este proyecto es una aplicación para gestionar información sobre libros y autores. Permite buscar libros, listar libros guardados, listar autores, buscar libros por     
idioma, y más.

## Estructura Del Proyecto:
  El proyecto tiene la siguiente estructura de directorios: 
  
  -src/main/java/com/alurachallenge/challenge_literatura-
  
        model/: Contiene las clases de modelo como Autor, Libro, y varias clases de datos.
        principal/: Contiene la clase Principal que parece ser el punto de entrada principal.
        repository/: Contiene las interfaces de repositorio como AutorRepository y LibroRepository.
        service/: Contiene las clases de servicio para consumir APIs y convertir datos (ConsumoAPI, ConvierteDatos, IConvierteDatos).
        ChallengeLiteraturaApplication.java: La clase principal de la aplicación Spring Boot. 

    -src/main/resources-
    
        application.properties: Archivo de configuración de la aplicación. 
        
    -src/test/java/com/alurachallenge/challenge_literatura-
    
        ChallengeLiteraturaApplicationTests.java: Contiene las pruebas unitarias para la aplicación.
        .gitignore: Archivo para especificar qué archivos deben ser ignorados por Git.
        HELP.md: Archivo de ayuda del proyecto.
        pom.xml: Archivo de configuración de Maven.
        mvnw y mvnw.cmd: Wrappers de Maven para garantizar que la versión correcta de Maven se utilice.

## Funcionalidades
    1-. Buscar libro ingresado
    2-. Listar libros guardados
    3-. Listar autores guardados
    4-. Listar autores por fecha ingresada
    5-. Listar libros por idioma
    6-. Listar libros más descargados

## Requisitos Previos
    -Java 11 o superior
    -Maven 3.6.3 o superior

## Instalación
    -Clona el repositorio:
    
      git clone https://github.com/tu-usuario/challenge-literatura.git
      
    -Navega al directorio del proyecto:
    
      cd challenge-literatura
      
    -Construye el proyecto usando Maven:
    
      ./mvnw clean install

## Ejecución
  Para ejecutar la aplicación, usa el siguiente comando:
  
    ./mvnw spring-boot:run

## Uso
  Una vez que la aplicación esté en ejecución, sigue las instrucciones en la consola para interactuar con las funcionalidades disponibles.

## Contribución
  Si deseas contribuir a este proyecto, por favor sigue estos pasos:
  
    -Haz un fork del repositorio.
    
    -Crea una rama (git checkout -b feature/nueva-funcionalidad).
    
    -Realiza tus cambios y haz commit (git commit -am 'Agrega nueva funcionalidad').
    
    -Sube tus cambios (git push origin feature/nueva-funcionalidad).
    
    -Abre un Pull Request.
