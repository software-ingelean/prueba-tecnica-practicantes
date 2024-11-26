## **Planteamiento de proyectos**

### Problema 1: Sistema de Gestión de Reservas  
#### **Contexto**:

Eres contratado para diseñar un sistema de gestión de reservas para un pequeño cine local. El sistema debe permitir a los clientes:

1. Ver la cartelera de películas.
2. Reservar asientos para una función específica.
3. Cancelar sus reservas.

Además, los administradores del cine deben poder:

1. Agregar nuevas películas y funciones.
2. Ver las estadísticas de ventas por función.

#### **Requisitos del sistema:**

1. Cada película tiene un título, una duración y un género.
2. Cada función tiene una película, una fecha y hora específica, y una sala asociada (con un número fijo de asientos).
3. Los clientes deben ingresar su nombre y correo electrónico para hacer reservas.
4. Un asiento puede reservarse solo una vez por función.

#### **Tareas:**

1. **Identificar los componentes del sistema:**
    - Describe las entidades principales y sus atributos.
    
2. **Estructurar la solución:**
    - Diseña las clases o módulos necesarios para implementar el sistema.
    - Indica las relaciones entre las entidades (por ejemplo, "una película tiene muchas funciones").
    
3. **Definir interacciones:**
    - Describe cómo los clientes y los administradores interactuarán con el sistema.
    - ¿Qué acciones específicas deben realizar? (Por ejemplo: reservar asiento, cancelar reserva, etc.)
    
4. **Esbozar un diseño básico:**
    - Opcional: Proporciona un diagrama simple de clases, un esquema de base de datos o un flujo de trabajo que represente el sistema.

#### **Formato de entrega:**
1. Una lista de las entidades principales y sus atributos.
2. La descripción de las clases o módulos, junto con sus métodos principales.
3. Un breve diagrama o pseudocódigo que muestre el flujo principal (opcional).

---

### **Problema 2: Biblioteca Digital**

#### **Contexto:**

Estás desarrollando una API para una biblioteca digital. Tu tarea es diseñar una estructura en formato JSON para representar los datos de la biblioteca. Los requisitos son los siguientes:

1. **Libros:**
    - Cada libro tiene un título, un autor, una lista de géneros, y un identificador único.
    - También debe incluir la cantidad de copias disponibles y el número total de copias.
      
2. **Autores:**
    - Cada autor tiene un nombre, una biografía breve y una lista de libros que ha escrito.
      
3. **Usuarios:**
    - Cada usuario tiene un nombre, un correo electrónico y una lista de libros que ha tomado prestados.
    - Por cada libro prestado, debe registrarse la fecha de préstamo y la fecha de devolución esperada.
      
4. **Géneros:**
    - Cada género tiene un nombre y una descripción.


#### **Tareas:**

1. **Diseña la estructura JSON:**
    - Crea una estructura JSON que represente estos datos.
    - Asegúrate de incluir relaciones claras entre libros, autores, géneros y usuarios.
      
2. **Piensa en la organización:**
    - Decide si algunos datos deberían ser referenciados por identificadores (por ejemplo, IDs de autores o géneros) o si deben incluirse directamente como parte del objeto.
      
3. **Agrega un ejemplo de datos:**
    - Llena la estructura con datos de ejemplo, con al menos:
        - 3 libros.
        - 2 autores.
        - 2 géneros.
        - 2 usuarios con al menos un libro prestado.


#### **Formato de entrega:**

Los candidatos deben entregar un archivo JSON bien estructurado con los datos de ejemplo y justificar cualquier decisión importante.
