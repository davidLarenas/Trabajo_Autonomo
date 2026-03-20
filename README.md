# Trabajo_Autonomo

Descripción breve
- Proyecto para gestión de datos.

Requisitos
- Maven/Gradle 

Estructura
- src/ : código fuente
- lib/ : dependencias 
- data/ : ficheros de ejemplo
- .gitignore : reglas de exclusión

Cómo compilar y ejecutar (Windows)
- Compilar con javac:
  - powershell/cmd:
    - javac -d out $(Get-ChildItem -Recurse -Filter *.java | ForEach-Object FullName)
  - ejecutar:
    - java -cp out paquete.Principal
- Con Maven:
  - mvn clean package
  - java -jar target/tu-artifact.jar

Pruebas
- mvn test  
- gradle test 


