| Palabra Clave | Definición | Ejemplo |
|---|---|---|
| `False` | Es el valor booleano de falso. Se utiliza en expresiones lógicas y condicionales. | `x = 5 > 10`<br> `print(x)`<br> `False` |
| `None` | Representa la ausencia de un valor. A menudo se usa para inicializar variables o como valor de retorno de funciones que no devuelven nada explícitamente. | `resultado = None`<br> `def mi_funcion(): pass`<br> `print(mi_funcion())`<br> `None` |
| `True` | Es el valor booleano de verdadero. Se utiliza en expresiones lógicas y condicionales. | `x = 10 > 5`<br> `print(x)`<br> `True` |
| `and` | Operador lógico que devuelve `True` si ambas expresiones a cada lado son verdaderas. | `if a > 0 and b < 10:`<br> `print("Ambas condiciones se cumplen")` |
| `as` | Se usa para crear un alias o dar un nombre alternativo a un módulo o a un archivo en una sentencia with. | `import math as m`<br> `print(m.sqrt(16))` |
| `assert` | Una declaración de depuración que verifica si una condición es verdadera. Si es falsa, lanza un error. | `def dividir(a, b):`<br> `assert b != 0, "No se puede dividir por cero"` |
| `break` | Termina la ejecución del bucle más cercano que lo contiene. | `for i in range(5):`<br> `if i == 3: break`<br> `print(i)`<br> `0 1 2` |
| `class` | Se utiliza para definir una nueva clase, que es una plantilla para crear objetos. | `class Persona:`<br> `def __init__(self, nombre): self.nombre = nombre` |
| `continue` | Salta el resto del código dentro del bucle actual y pasa a la siguiente iteración. | `for i in range(5):`<br> `if i == 2: continue`<br> `print(i)`<br> `0 1 3 4` |
| `def` | Se utiliza para definir una función o un método. | `def saludar(nombre):`<br> `print(f"Hola, {nombre}")` |
| `del` | Se usa para eliminar objetos, variables o elementos de una lista, tupla o diccionario. | `mi_lista = [1, 2, 3]`<br> `del mi_lista[1]`<br> `print(mi_lista)`<br> `[1, 3]` |
| `elif` | Abreviatura de "else if", se utiliza en declaraciones condicionales para probar múltiples condiciones. | `if x > 10:`<br> `print("Mayor que 10")`<br> `elif x == 10:`<br> `print("Es 10")` |
| `else` | Se usa en declaraciones condicionales (`if`) para ejecutar un bloque de código cuando las condiciones anteriores son falsas. | `if edad >= 18:`<br> `print("Adulto")`<br> `else:`<br> `print("Menor de edad")` |
| `except` | Se utiliza junto con `try` para manejar errores (excepciones) que puedan ocurrir durante la ejecución. | `try:`<br> `print(10 / 0)`<br> `except ZeroDivisionError:`<br> `print("Error: División por cero")` |
| `for` | Se usa para crear un bucle que itera sobre una secuencia (como una lista, tupla, cadena o diccionario). | `frutas = ["manzana", "banana"]`<br> `for fruta in frutas:`<br> `print(fruta)` |
| `from` | Se usa junto con `import` para importar partes específicas de un módulo. | `from math import sqrt`<br> `print(sqrt(9))` |
| `global` | Indica que una variable es global y no local a la función. | `x = 5`<br> `def mi_funcion(): global x; x = 10` |
| `if` | Se utiliza para crear una declaración condicional que ejecuta un bloque de código solo si una condición es verdadera. | `if 5 > 2:`<br> `print("Correcto")` |
| `import` | Se usa para traer un módulo o biblioteca a tu programa. | `import random`<br> `print(random.randint(1, 10))` |
| `in` | Se utiliza para verificar si un valor está presente en una secuencia. También se usa en los bucles `for`. | `if "a" in "manzana":`<br> `print("Sí está")` |
| `is` | Operador que verifica si dos variables apuntan al mismo objeto en la memoria, no solo si tienen el mismo valor. | `a = [1, 2]`<br> `b = [1, 2]`<br> `print(a is b)`<br> `False` |
| `lambda` | Se usa para crear funciones anónimas, pequeñas y de una sola línea. | `suma = lambda a, b: a + b`<br> `print(suma(2, 3))`<br> `5` |
| `nonlocal` | Se utiliza en una función anidada para indicar que una variable no es local a esa función, sino que pertenece a la función externa. | `def externa():`<br> `x = 5`<br> `def interna(): nonlocal x; x = 10` |
| `not` | Operador lógico que invierte el valor de una expresión booleana. | `es_par = 4 % 2 == 0`<br> `print(not es_par)`<br> `False` |
| `or` | Operador lógico que devuelve `True` si al menos una de las expresiones es verdadera. | `if a > 0 or b < 0:`<br> `print("Al menos una es verdadera")` |
| `pass` | Es una instrucción nula. Se usa como marcador de posición cuando una declaración es requerida sintácticamente pero no quieres que el código haga nada. | `def mi_funcion_vacia(): pass` |
| `raise` | Se usa para forzar que ocurra una excepción específica. | `if temperatura > 50:`<br> `raise ValueError("¡Hace mucho calor!")` |
| `return` | Se usa para salir de una función y, opcionalmente, devolver un valor. | `def get_pi():`<br> `return 3.14159` |
| `try` | Se utiliza para encerrar el código que podría lanzar una excepción, permitiendo manejarla sin que el programa se detenga. | `try:`<br> `print(10 / 0)` |
| `while` | Crea un bucle que se ejecuta mientras una condición sea verdadera. | `i = 0`<br> `while i < 3:`<br> `print(i)`<br> `i += 1` |
| `with` | Se usa para envolver la ejecución de un bloque de código con métodos definidos por un manejador de contexto. | `with open("archivo.txt", "r") as f:`<br> `contenido = f.read()` |
| `yield` | Se usa en una función para convertirla en un generador. | `def cuenta_regresiva(n):`<br> `while n > 0: yield n; n -= 1` |
