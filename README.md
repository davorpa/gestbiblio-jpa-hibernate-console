# gestbiblio-jpa-hibernate-console

Gestión de préstamos en una biblioteca - librería


## Requisitos

Se quiere implementar el sistema informático para la gestión de una biblioteca. Las especificaciones funcionales son las siguientes:

- Se tienen distintas categorías literarias, entre las que se destacan [1.] Novela, [2.] Teatro, [3.] Poesía y [4.] Ensayo. Estas categorías deben ser gestionables por la aplicación (CRUD).
- En la biblioteca se encuentran libros, que tendrán los siguientes atributos: código, título, ISBN, categoría, autor, editorial.
- Los autores son otra entidad importante en nuestro modelo, por lo que también ser gestionará el alta, baja y modificación de los mismos.
- De cada libro existirá un número finito de copias, que tendrán un identificador y un estado: [1.] en la biblioteca, [2.] prestada, [3.] con retraso y [4.] en reparación.
- Se tendrán registrados usuarios, que contarán con una clave alfanumérica que los identifique de manera inequívoca.
- Cada uno de los usuarios puede ser un máximo de tres libros prestados, y se debe llevar un registro del histórico de usuarios que han cogido prestada cada una de las copias.

Se pide:

1. Diagrama UML de entidad - relación del modelo de dominio.
2. Diagrama UML de base de datos SQL y su correspondiente script de creación de tablas.
3. Diagrama UML de clases así como hacer una pequeña aplicación de consola que permita hacer las operaciones CRUD básicas sobre las entidades del modelo de dominio.
