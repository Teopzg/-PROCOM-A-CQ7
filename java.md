Palabra Clave	Definición	Ejemplo
abstract	Se utiliza para declarar una clase o método que debe ser implementado por una subclase no abstracta.	public abstract class Forma { abstract void dibujar(); }
boolean	Tipo de dato que solo puede tener los valores true o false.	boolean estaAbierto = true;
byte	Tipo de dato que almacena enteros de 8 bits con signo.	byte valorPequeño = 12;
case	Se utiliza dentro de la declaración switch para marcar bloques de código a ejecutar.	case 1: System.out.println("Uno"); break;
catch	Se utiliza para capturar y manejar una excepción lanzada en un bloque try.	catch (IOException e) { e.printStackTrace(); }
char	Tipo de dato para almacenar un solo carácter Unicode de 16 bits.	char letra = 'A';
const	Reservada pero no utilizada actualmente; tiene una función similar a final.	(Reservada, no tiene un uso estándar)
default	Se utiliza en la declaración switch para el código a ejecutar si ningún caso coincide.	default: System.out.println("Otro");
do	Se utiliza para crear un bucle do-while que ejecuta el código al menos una vez.	do { i++; } while (i < 5);
double	Tipo de dato para números de punto flotante de doble precisión (64 bits).	double precio = 99.99;
enum	Se utiliza para declarar un tipo enumerado, un conjunto fijo de constantes.	public enum Dia { LUNES, MARTES }
extends	Indica que una clase hereda de otra clase, obteniendo sus propiedades y métodos.	class Perro extends Animal { ... }
final	Indica que el valor de una variable no puede cambiar, o que una clase no puede tener subclases.	final int MAX_TAM = 100;
finally	Se utiliza con try-catch para un bloque de código que siempre se ejecutará, ocurra o no una excepción.	finally { System.out.println("Limpieza completada"); }
float	Tipo de dato para números de punto flotante de precisión simple (32 bits).	float tasa = 0.5f;
implements	Se utiliza en la declaración de una clase para indicar que implementa una interfaz.	class Coche implements Movible { ... }
instanceof	Operador que verifica si un objeto es una instancia de una clase o interfaz específica.	if (obj instanceof String) { ... }
int	Tipo de dato principal para almacenar enteros de 32 bits con signo.	int contador = 0;
interface	Se utiliza para declarar una interfaz, una colección de métodos abstractos y constantes.	public interface Movible { void mover(); }
long	Tipo de dato para enteros de 64 bits, usado para números grandes.	long poblacionMundial = 8000000000L;
native	Indica que un método está implementado en código dependiente de la plataforma (como C/C++).	native void hacerAlgoNativo();
new	Se utiliza para crear una nueva instancia de una clase (un objeto).	String nombre = new String("Java");
package	Se utiliza para agrupar clases, interfaces y subpaquetes en un solo nombre.	package com.miempresa.app;
private	Un modificador de acceso que hace que un miembro (variable o método) solo sea accesible dentro de su propia clase.	private int edad;
protected	Un modificador de acceso que permite el acceso dentro del mismo paquete y por subclases.	protected String modelo;
public	Un modificador de acceso que hace que un miembro o clase sea accesible desde cualquier otra clase.	public static void main(String[] args) { ... }
short	Tipo de dato que almacena enteros de 16 bits con signo.	short numDias = 365;
static	Indica que un miembro pertenece a la clase en sí misma, en lugar de a una instancia específica (objeto).	public static int contar = 0;
super	Se refiere a la superclase inmediata (clase padre) de la clase actual.	super.metodoPadre();
synchronized	Se utiliza para el control de concurrencia, garantizando que un bloque de código solo sea ejecutado por un hilo a la vez.	public synchronized void depositar(double cantidad) { ... }
this	Se refiere a la instancia actual (objeto) de la clase.	this.nombre = nombre;
throw	Se utiliza para lanzar explícitamente una excepción.	throw new IllegalArgumentException("Valor inválido");
throws	Se utiliza en la firma de un método para declarar las excepciones que podría lanzar.	public void leerArchivo() throws IOException { ... }
transient	Indica que una variable no debe ser serializada cuando el objeto se guarda.	private transient String password;
void	Indica que una función o método no devuelve ningún valor.	public void imprimirMensaje() { ... }
volatile	Se utiliza para el manejo de hilos, indicando que una variable puede ser modificada por diferentes hilos.	private volatile boolean estaCorriendo = false;
