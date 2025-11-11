# TraduccionPorSintaxis

##Descripcion:
Este repositorio es de un analizador de expresiones aritméticas en un zip tambien con las pruebas esta esta utilizando una traduccion dirigido por Sintaxis. El sistema procesa expresiones matemáticas. El analizador sintáctico construye un Árbol de Sintaxis Abstracta y se hizo una tabla de símbolos (TablaSimbolos)  entrada que son las entradas, la implementacion de F,F,P que es la que vendria a ayudar a la computadora a leer y entender la forma de una expresión.

**Requisitos**
- Python 3.7+

Ejecucion:
```bash
python Gramatica.py Prueba.txt
```

- Gramática LL(1) sin recursión izquierda.
- Implementación de los conjuntos F (FIRST), S (FOLLOW) y P (Predicción).
- Construcción del AST decorado.
- Tabla de símbolos
