El objetivo principal es terminar de implementar y desarrollar la gestión de citas del proyecto de Backend. Este proyecto utiliza versiones antiguas de JAVA, en concreto JAVA 8. Se pide por tanto desarrollar las siguientes tareas:

1. Tu primera tarea va a ser crear citas mediante la API. Debes tener en cuenta las limitaciones en cuanto a la creación de citas. Asegúrate de cumplir con las especificaciones hechas en JUnit, ya que son una ayuda esencial para el desarrollo de código. Solamente se requiere modificar el archivo AppointmentController.java.

2. La segunda tarea tiene relación con que las entidades creadas no están siendo "testeadas", y por lo tanto, pueden surgir posibles errores debido a una mala implementación. Para solucionar esto, se deben crear diferentes pruebas "JUnit" para cada una de las entidades en el archivo EntityUnitTest.java, así como cada uno de los controladores de estas entidades en el archivo EntityControllerUnitTest.java, que se encuentra en el directorio de pruebas.

3. Asegúrate realizar código limpio. Como estás trabajando en un hospital, se espera que sigas medidas estrictas para garantizar que el código sea aceptable. Por lo tanto, debes escribir código que esté libre de errores y vulnerabilidades, especialmente de vulnerabilidades.

4. Se quiere hacer un despliegue escalable de la API, para ello se plantea usar Kubernetes. Cree un Dockerfile que permita ejecutar una base de datos MySQL y el microservicio. Para este último requerimiento, se solicita un Dockerfile Multistage donde se ejecuten primero las pruebas, y si todas pasan, se compile y ejecute el microservicio. Los nombres de los Dockerfiles serán Dockerfile.mysql y Dockerfile.maven, respectivamente.

*Extra OPCIONAL: Desarrolla un diagrama UML con todas las relaciones entre clases. Se valorará positivamente la documentación dentro del repositorio.

*IMPORTANTE: AppointmentController.java', 'EntityUnitTest.java' y 'EntityControllerUnitTest.java' son los únicos archivos modificables. El resto de archivos NO lo son y están protegidos.