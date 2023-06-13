## Sobre el Sistema

Este proyecto se basa en el sistema de gestión de cuentas y mantenimiento de estados financieros. El propósito del sistema de gestión contable es mantener un registro de los fondos recibidos, utilizados, difundidos y donados por una organización. Los detalles de las transacciones y el mantenimiento de un presupuesto y el recuento del saldo/inventario actual en efectivo/especie se incorporan a este sistema.

El sistema requiere que el usuario tenga las credenciales apropiadas, es decir, derechos de Administrador o Contador. Dependiendo de la autoridad de acceso, se muestra un menú de posibles acciones y cada opción conduce a una función que realiza las operaciones deseadas en archivos binarios mediante el uso de objetos de clase relevante. 

Las características y funcionalidad del sistema son las siguientes:

- Interfaz de inicio de sesión (se bifurca en niveles de acceso de administrador y contable)
- Nivel de acceso como Administrador o Superusuario
- Nivel de acceso como uno de los 10 contadores predefinidos

- Panel/Menú del administrador:
  - Ingrese los detalles iniciales de la cuenta
  - Ingresar al historial de transacciones
  - Mostrar historial de transacciones - Estado de cuenta detallado
  - Asignar transacciones actuales al presupuesto, gastos e ingresos
  - Mostrar presupuesto, ingresos y gastos únicamente
  - Modificar los detalles de la transacción
  - Mostrar los detalles de los contadores
Salir de la aplicación

- Panel/Menú Contador:
  - Mostrar historial de transacciones - Estado de cuenta detallado 
  - Mostrar presupuesto, ingresos y gastos únicamente
  - Mostrar Contadores
  - Salir de la aplicación

## Acerca de la Implementación del Programa

El sistema ha sido implementado a través del uso de varias construcciones y métodos de programación. Sigue el concepto de Programación Orientada a Objetos a través del uso de Clases y Objetos para crear una clase para definir las propiedades de las transacciones. Se incorpora el concepto de Manejo de Archivos mediante el uso de archivos binarios, para crear y mantener un registro de las transacciones que se realizan. Los comentarios están presentes en todo el programa para indicar las funciones y necesidades de cada componente del sistema. El sistema aprovecha al máximo los conceptos enseñados en Ciencias de la Computación en las clases XI y XII, para garantizar la claridad y la buena organización del programa.

El programa incluye dos estructuras, **CUENTA y ARTÍCULO,** y una clase **TRANSACCIÓN**. La estructura **CUENTA** se utiliza para representar las credenciales de inicio de sesión de un contador individual, es decir, el nombre de usuario y la contraseña. La estructura **ARTÍCULO** representa los detalles de cualquier producto/artículo que la empresa compra o vende. La clase **TRANSACCIÓN** se utiliza para representar los detalles de cada transacción financiera de la empresa y para realizar operaciones en esa transacción. Todas las transacciones se almacenan en un archivo binario, **CMPNYACC.DAT**, en forma de objetos de la clase que se adjuntan, para mantener también registros de transacciones anteriores. Los fondos y gastos iniciales de la empresa se almacenan en otro archivo binario, **ACCDET.DAT,** para cotejar y mantener un registro del saldo de la cuenta.
