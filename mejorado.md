| Término | Definición | Ejemplo (en Java) |
| **abstract** | Define una clase que no puede ser instanciada o un método sin implementación. | `public abstract class Animal { ... }` |
| **Abstracción** | Oculta la **complejidad** y solo muestra la funcionalidad esencial (con interfaces/clases abstractas). | `vehiculo.acelerar();` |
| **Algoritmo** | Conjunto **ordenado** de instrucciones para resolver un problema. | `for (int i = 0; i < n; i++) { ... }` |
| **Argumento** | Valor que se **pasa** a un método cuando se llama. | `saludar("Mundo")` |
| **Argumentos Clave** | Argumentos pasados a un método usando el **nombre** del parámetro (se asemeja a Builders en Java). | *(En Java, se usa un Builder Pattern)* |
| **Array** | Estructura de datos que almacena una **colección** de elementos del mismo tipo y de tamaño fijo. | `int[] numeros = new int[10];` |
| **ArrayList** | Clase de colección que implementa una **lista redimensionable** (dinámica). | `ArrayList<String> lista = new ArrayList<>();` |
| **ArrayDeque** | Implementación de una cola de doble extremo (**Deque**) que se puede usar como pila o cola. | `ArrayDeque<String> stack = new ArrayDeque<>();` |
| **assert** | Palabra clave para realizar una prueba que se verifica en tiempo de ejecución para detectar **bugs**. | `assert x > 0 : "x debe ser positivo";` |
| **Asignación** | La acción de **dar** un valor a una variable. | `int x = 10;` |
| **Atributo** | Variable o dato que pertenece a una **clase** u objeto (sinónimo de campo). | `public String color;` |
| **Autoboxing** | Conversión **automática** de tipos primitivos a sus clases envoltorio (ej. `int` a `Integer`). | `Integer x = 5;` |
| **Backend** | La parte de una aplicación que se ejecuta en el **servidor** (lógica y datos). | *(Se ejecuta el código Java del servidor)* |
| **boolean** | Tipo de dato primitivo que solo puede ser **true** (verdadero) o **false** (falso). | `boolean isActive = true;` |
| **break** | Palabra clave que se usa para **salir** inmediatamente de un ciclo (`for`, `while`) o un `switch`. | `while (true) { if (i == 5) break; }` |
| **byte** | Tipo de dato primitivo que almacena números enteros en un rango pequeño (8 bits). | `byte b = 100;` |
| **case** | Palabra clave usada dentro de la estructura **switch** para marcar bloques de código a ejecutar. | `case 1: System.out.println("Uno"); break;` |
| **catch** | Palabra clave que define el bloque de código para **manejar** una excepción lanzada en el bloque `try`. | `catch (IOException e) { ... }` |
| **char** | Tipo de dato primitivo que almacena un solo **carácter** (16 bits, Unicode). | `char c = 'A';` |
| **Checked Exception** | Tipo de excepción que el compilador **obliga** a manejar con `try-catch` o declarar con `throws`. | `IOException` |
| **class** | Palabra clave fundamental que se usa para **definir** una clase. | `public class Coche { ... }` |
| **Clase Abstracta** | Una clase que **no puede ser instanciada** directamente y se usa como plantilla base. | `public abstract class Base { ... }` |
| **Cloneable** | Interfaz de marcador que indica que una clase permite la **clonación** de objetos. | `class MyClass implements Cloneable { ... }` |
| **Colección** | Interfaz que es la **raíz** de la jerarquía de colecciones (List, Set, Queue). | `import java.util.Collection;` |
| **Colección** | Un marco de trabajo para representar grupos de objetos (List, Set, Map). | `List<String> nombres;` |
| **Comentario** | Texto ignorado por el compilador, usado para **explicar** el código. | `// Esto es un comentario de una línea` |
| **Compilación** | Proceso de traducción del código fuente Java (`.java`) a **bytecode** (`.class`). | *(Se ejecuta con javac)* |
| **Concurrencia** | La capacidad de un programa para ejecutar **varias tareas** lógicamente al mismo tiempo (hilos). | `synchronized (this) { ... }` |
| **Condición** | Una **expresión** que se evalúa a `true` o `false`. | `(x > 10)` |
| **Constante** | Un valor **fijo** que no puede cambiar (usando `final` y `static`). | `public static final int MAX = 100;` |
| **Constructor** | Método especial que se llama al **crear** una nueva instancia con `new`. | `public class Coche() { ... }` |
| **continue** | Palabra clave que salta el resto del código en el ciclo actual y pasa a la **siguiente iteración**. | `for (int i = 0; i < 5; i++) { if (i == 2) continue; }` |
| **default** | Palabra clave dentro de `switch` que define el código a ejecutar si ninguna **condición** `case` coincide. | `default: System.out.println("Otro");` |
| **do** | Palabra clave que inicia un ciclo `do-while`, garantizando que el código se **ejecuta al menos una vez**. | `do { i++; } while (i < 5);` |
| **double** | Tipo de dato primitivo para números de **coma flotante** de doble precisión (64 bits). | `double precio = 19.99;` |
| **else** | Palabra clave que define un bloque de código a ejecutar cuando la **condición** `if` es **falsa**. | `if (x > 10) { ... } else { ... }` |
| **Encapsulamiento** | Principio de POO que **restringe** el acceso directo a los datos internos (usando `private` y *getters/setters*). | `private int saldo; public int getSaldo() { ... }` |
| **enum** | Tipo especial de clase que representa un grupo fijo de **constantes** (enumeraciones). | `public enum Dia { LUNES, MARTES }` |
| **Enumeración** | Ver palabra clave **enum**. | `Dia.LUNES` |
| **Error** | Problema **grave** (ej. desbordamiento de memoria) que no se espera que el programa maneje. | `OutOfMemoryError` |
| **Excepción** | Un evento que interrumpe el flujo normal, pero que puede ser **manejado**. | `try...catch` |
| **Excepción No Verificada** | Tipo de excepción que **no** requiere manejo explícito (subclases de `RuntimeException`). | `NullPointerException` |
| **extends** | Palabra clave que indica que una clase **hereda** de otra (establece la subclase). | `class Perro extends Animal { ... }` |
| **final** | Indica que una variable es una **constante**, una clase no puede tener subclases, o un método no puede ser sobrescrito. | `final int MAX_VALOR = 100;` |
| **Finalizar** | Método (`finalize()`) que se llama antes de que el **Garbage Collector** destruya un objeto (obsoleto). | `protected void finalize() { ... }` |
| **finally** | Define el bloque de código que **siempre se ejecuta**, haya o no excepción en `try`. | `try { ... } finally { archivo.close(); }` |
| **float** | Tipo de dato primitivo para números de **coma flotante** de precisión simple (32 bits). | `float f = 3.14f;` |
| **for** | Palabra clave para crear un ciclo que **itera** un número predefinido de veces o sobre una colección. | `for (int i = 0; i < 10; i++) { ... }` |
| **Frontend** | La parte de una aplicación con la que **interactúa** el usuario (interfaz). | *(Se comunica con el servidor Java)* |
| **Garbage Collector** | Proceso de Java que **libera** automáticamente la memoria ocupada por objetos que ya no se usan. | *(Se ejecuta automáticamente por la JVM)* |
| **Generics** | Permite crear clases, métodos e interfaces que funcionan con **cualquier tipo** de dato (ej. `List<T>`). | `List<String> nombres;` |
| **Getter** | Un **método** que se usa para obtener (leer) el valor de un atributo. | `public int getEdad() { return edad; }` |
| **HashCode** | Un valor entero que representa la **identidad** de un objeto, usado principalmente en tablas hash. | `obj.hashCode()` |
| **Herencia** | Principio de POO donde una **clase** adquiere propiedades y métodos de otra (usando `extends`). | `class Gato extends Animal { ... }` |
| **Identificador** | Nombre dado a una **variable**, método, clase, etc. | `miVariable` |
| **if** | Palabra clave que ejecuta un bloque de código solo si una condición es verdadera. | `if (edad >= 18) { ... }` |
| **implements** | Palabra clave que indica que una clase está obligada a proporcionar la implementación de una **interfaz**. | `class Coche implements Rueda { ... }` |
| **import** | Palabra clave que se usa para **incluir** clases o paquetes externos. | `import java.util.Scanner;` |
| **Inmutable** | Objeto cuyo estado **no puede ser cambiado** después de su creación (ej. `String`). | `String s = "Hola";` |
| **Inicializador** | Bloque de código que se ejecuta cuando se **carga** una clase (`static`) o se crea una instancia. | `static { System.out.println("Cargando"); }` |
| **InputStream** | Clase abstracta para leer **bytes** desde una fuente (ej. archivo o red). | `FileInputStream fis;` |
| **instanceof** | Operador que verifica si un objeto es una **instancia** de una clase o interfaz específica. | `if (obj instanceof String) { ... }` |
| **Instancia** | Un objeto **concreto** creado a partir de una clase. | `Coche miCoche = new Coche();` |
| **int** | Tipo de dato primitivo para números enteros de 32 bits. | `int edad = 30;` |
| **interface** | Tipo de dato abstracto que define un **contrato** de métodos que una clase debe implementar. | `public interface Rueda { ... }` |
| **Javadoc** | Herramienta que genera **documentación** HTML a partir de los comentarios especiales del código fuente. | `/** Comentario Javadoc */` |
| **JIT** | Compilador "Just-In-Time" que convierte el bytecode de Java en código máquina en tiempo de ejecución. | *(Parte de la JVM)* |
| **JVM** | Máquina **Virtual** de Java; el entorno de ejecución que interpreta y ejecuta el bytecode. | *(La plataforma donde corre Java)* |
| **Lambda** | Una **función anónima** (introducida en Java 8) que se usa para implementar interfaces funcionales. | `(a, b) -> a + b` |
| **long** | Tipo de dato primitivo para números enteros de 64 bits (rango muy grande). | `long l = 1234567890123L;` |
| **Map** | Interfaz de colección que almacena pares de **clave-valor** (no hereda de Collection). | `HashMap<String, Integer> mapa;` |
| **Método** | Una **función** que pertenece a una clase (define el comportamiento del objeto). | `public void acelerar() { ... }` |
| **Método Principal** | El punto de **entrada** de la aplicación Java. | `public static void main(String[] args) { ... }` |
| **Modificador** | Una palabra clave que **cambia** la declaración de una clase, método o variable (ej. `public`, `static`). | `public static final` |
| **native** | Indica que un método está implementado en código **nativo** (ej. C/C++). | `public native void metodoNativo();` |
| **new** | Operador que se usa para **crear** una nueva instancia (objeto) de una clase. | `Coche miCoche = new Coche();` |
| **null** | La referencia especial que indica que una variable de objeto **no apunta** a ningún objeto. | `String s = null;` |
| **Objeto** | Instancia de una clase, **entidad** que combina datos y comportamiento. | `miObjeto` |
| **OutputStream** | Clase abstracta para escribir **bytes** en un destino. | `FileOutputStream fos;` |
| **Override** | Concepto de POO: un método en una subclase tiene la misma firma que uno en su superclase. | `@Override public void mover() { ... }` |
| **package** | Palabra clave que agrupa clases e interfaces **relacionadas**. | `package com.miempresa.app;` |
| **Parámetro** | El **nombre** usado en la definición de un método para recibir un valor. | `public void setEdad(int nuevaEdad)` |
| **private** | Modificador de acceso: el miembro solo es accesible **dentro de su propia clase**. | `private int saldo;` |
| **POO** | Programación **Orientada** a Objetos, paradigma basado en clases y objetos. | *(La base de Java)* |
| **Polimorfismo** | Permite que un **mismo** método se comporte de forma diferente según el objeto. | `animal.sonido()` |
| **protected** | Modificador de acceso: el miembro es accesible dentro de su paquete y por **subclases** (herencia). | `protected String nombre;` |
| **public** | Modificador de acceso: el miembro es accesible desde **cualquier** otra clase. | `public static void main(...) { ... }` |
| **Reflection** | API que permite a un programa **inspeccionar** y manipular sus propias clases, métodos y atributos en tiempo de ejecución. | `Class c = obj.getClass();` |
| **return** | Palabra clave que **termina** la ejecución de un método y devuelve un valor (si aplica). | `return resultado;` |
| **Serialización** | El proceso de **convertir** un objeto a una secuencia de bytes para almacenarlo o transmitirlo. | `FileOutputStream f = new FileOutputStream("data");` |
| **Setter** | Un **método** que se usa para establecer (modificar) el valor de un atributo. | `public void setEdad(int edad) { this.edad = edad; }` |
| **short** | Tipo de dato primitivo para números enteros de 16 bits. | `short s = 500;` |
| **Sobrecarga** | Cuando varios métodos tienen el **mismo nombre** pero diferentes listas de parámetros (Overloading). | `void f(int a); void f(String s);` |
| **static** | Modificador que indica que un miembro pertenece a la **clase** misma, no a una instancia específica. | `public static final double PI = 3.14;` |
| **String** | Clase (no primitivo) que representa una **secuencia de caracteres** de forma inmutable. | `String nombre = "Ana";` |
| **Streams** | (Java 8) Secuencia de elementos que soporta operaciones **funcionales** (filtrado, mapeo, etc.). | `lista.stream().filter(...).collect(...)` |
| **strictfp** | Restringe los cálculos de **punto flotante** para garantizar la portabilidad (raro). | `public strictfp class Calculadora { ... }` |
| **Subclase** | Una clase que **hereda** de otra (clase hija). | `class Perro extends Animal` |
| **super** | Se usa para referirse a miembros de la **superclase** (padre). | `super.metodoPadre();` |
| **Super** | (Adicional) Se usa para **llamar** al constructor de la superclase. | `super(nombre);` |
| **switch** | Sentencia de **control** de flujo que permite seleccionar un camino de ejecución entre muchos. | `switch (dia) { ... }` |
| **synchronized** | Modificador para **controlar** el acceso de múltiples hilos a un bloque de código (concurrencia). | `public synchronized void add(int val) { ... }` |
| **this** | Referencia a la **instancia** actual del objeto. | `this.nombre = nombre;` |
| **this** | (Adicional) Se usa para **llamar** a otro constructor de la misma clase. | `this(0);` |
| **throw** | Palabra clave que se usa para **lanzar** explícitamente una excepción. | `throw new IllegalArgumentException("Inválido");` |
| **throws** | Usada en la **firma** de un método para declarar qué excepciones podría lanzar. | `public void leer() throws IOException { ... }` |
| **transient** | Modificador que marca un atributo para que sea **ignorado** durante la serialización. | `private transient String password;` |
| **try** | Palabra clave que inicia el bloque de código donde pueden ocurrir **excepciones** (manejo de errores). | `try { Scanner sc = new Scanner(archivo); }` |
| **Unchecked Exception**| Ver **Excepción No Verificada**. | `RuntimeException` |
| **Vector** | Clase de colección sincronizada y **obsoleta** similar a `ArrayList`. | `Vector<String> v = new Vector<>();` |
| **void** | Indica que un método **no** devuelve ningún valor. | `public void imprimir() { ... }` |
| **volatile** | Modificador de variable que indica que su valor podría ser **modificado** por diferentes hilos (visibilidad). | `private volatile boolean flag;` |
| **while** | Crea un ciclo que se **ejecuta** repetidamente mientras una condición booleana es **true**. | `while (scanner.hasNextLine()) { ... }` |
