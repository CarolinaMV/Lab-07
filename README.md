# Lab-07

## ORM MYBATIS

### SECCIÓN I. - INTRODUCCIÓN A JDBC

**1.** Clonar el proyecto MyBatis_Introduction_VideoRental de GitHub donde se realizará la implementación completa del laboratorio.
       ![image](https://user-images.githubusercontent.com/98135902/158256276-eea664f9-4a9a-4005-87fb-2b4de2e8c86c.png)

**2.** Descargue el archivo JDBCExample.java y agreguelo en el paquete "edu.eci.cvds.sampleprj.jdbc.example".
       ![image](https://user-images.githubusercontent.com/98135902/158258522-947649a5-e5c4-4daf-b6a9-4dd50a07b80a.png)

**3.** Desde esta clase se realizará una conexión a una base de datos MySQL por medio de JDBC y sus "Prepared Statements".

**4.** En un motor de base de datos SQL se tiene un esquema con el siguiente modelo de base de datos (para registrar pedidos sobre productos):
       ![image](https://user-images.githubusercontent.com/98135902/158255211-43120908-3f31-4b62-88f8-d4c9dd994f6d.png)

**5.** Revise la documentación de ‘PreparedStatement’, del API JDBC.

**6.** En la clase JDBCExample juste los parámetros de conexión a la base de datos con los datos reales:
       ![image](https://user-images.githubusercontent.com/98135902/158258835-013fb349-af81-47ea-9b3b-22d8814e6fce.png)


**7.** Implemente las operaciones faltantes:

        1. nombresProductosPedido
        2. valorTotalPedido - El resultado final lo debe retornar la base de datos, no se deben hacer operaciones en memoria.
        3. registrarNuevoProducto - Use su código de estudiante para evitar colisiones.
     
     ok

**8.** Verifique por medio de un cliente SQL, que la información retornada por el programa coincide con la que se encuentra almacenada en base de datos.

Para verificar la información retornada nos conectamos a la base bdprueba utilizando DBeaver:
![1](https://user-images.githubusercontent.com/79550161/158707521-101082f2-c02e-4065-873b-2a1a0edc143c.JPG)
![2](https://user-images.githubusercontent.com/79550161/158739407-d79f2800-1a40-41b0-841b-70d6f3616b73.JPG)

### SECCIÓN II. - INTRODUCCIÓN A MYBATIS

**1.** Revise la documentación básica de MyBatis de forma que entienda para qué sirve y el uso básico que se le puede dar al framework.

**2.** Seguir las instrucciones que se encuentran en el repositorio de forma que en la clase MyBatisExample.java se creen los mappers necesarios y sea posible realizar la              ejecución de diferentes sentencias SQL en la base de datos de pruebas.

#### Parte I (Para entregar en clase):

* Puntos hasta el 5:
![3](https://user-images.githubusercontent.com/79550161/158737857-747c3524-b1f0-451a-88bf-414b8dd7e0ff.JPG)

* Punto 6:
![4](https://user-images.githubusercontent.com/79550161/158739295-74c6f5c2-a7a4-4f6a-8883-e0b4785fcff3.JPG)

* Punto 7:
![5](https://user-images.githubusercontent.com/79550161/158742333-5a37e167-308d-49d8-81a4-77f1141d9f1e.JPG)

