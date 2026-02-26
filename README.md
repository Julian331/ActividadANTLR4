# ActividadANTLR4
# Ejemplo Diapositiva
Archivos principales
- *.g4 → Gramática correspondiente.
- Clases Java personalizadas.
- Archivos de prueba .txt.
Ejecución
antlr4 -visitor Nombre.g4
javac -cp .:/usr/share/java/antlr4-runtime.jar *.java
java -cp .:/usr/share/java/antlr4-runtime.jar ClasePrincipal < prueba.txt
Calculadora (Capítulo 4)
Archivos principales
- Calc.g4 → Gramática de la calculadora.
- EvalVisitor.java → Visitor personalizado para evaluar expresiones.
- CalcTest.java → Clase principal para ejecutar la calculadora.
- input.txt → Archivo de prueba con expresiones aritméticas.
# Ejecución
- antlr4 -visitor Calc.g4
- javac -cp .:/usr/share/java/antlr4-runtime.jar *.java
- java -cp .:/usr/share/java/antlr4-runtime.jar CalcTest < input.txt
