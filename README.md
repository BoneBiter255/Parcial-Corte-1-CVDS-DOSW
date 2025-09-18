# Parcial-Corte-1-CVDS-DOSW


Daniel Felipe Hueso Rueda 


Grupo 3 



1 <img width="1028" height="610" alt="image" src="https://github.com/user-attachments/assets/c52acbf6-8822-487c-baf1-42648ce9762b" />

2 <img width="376" height="458" alt="image" src="https://github.com/user-attachments/assets/6d23efe6-85e8-491c-9f8e-3ebbfd23752b" />


3<img width="623" height="427" alt="image" src="https://github.com/user-attachments/assets/1e30332c-1158-46fc-9406-7876b4e0a3e8" />
(ademas de los archivos agregados a el repositorio en docs imagenes y uml)

4 Patron Factory Method
Factory Method
Creacional
Se utiliza para crear objetos de diferentes tipos de pagos (por ejemplo, PagoPayPal, PagoTarjetaCredito, PagoCriptomoneda) sin especificar la clase concreta que se va a instanciar.
Permite que la logica de creacion de objetos este centralizada en una "fabrica" (por ejemplo, FabricaPayPal, FabricaTarjetaCredito, etc.), facilitando la extension y el mantenimiento.
En el diagrama de clases, se refleja con una jerarquia de fabricas y productos, donde una interfaz o clase abstracta define el metodo de creacion y las subclases concretas implementan la creacion de cada tipo de pago.

Patron Observer
Nombre del Patron: Observer
Tipo de Patron: Comportamiento
Se utiliza para notificar automaticamente a varios observadores  cuando ocurre un evento relevante en el sistema de pagos.
Permite desacoplar el emisor de eventos  de los receptores , facilitando la extension y el mantenimiento.
En el diagrama de clases, se refleja con una relacion entre el sujeto (por ejemplo, ProcesadorPagos) y una lista de observadores que implementan una interfaz comun, recibiendo notificaciones cuando se realiza un pago.


5)<img width="928" height="291" alt="image" src="https://github.com/user-attachments/assets/486145f6-a5f7-496b-a067-fe1b1c20450c" />

6)en rama test

7)<img width="1251" height="337" alt="image" src="https://github.com/user-attachments/assets/43f020b4-6685-4183-afcc-6526c72b2e66" />


8 ) 


9) 1 Abrir una terminal en la carpeta raíz del proyecto (donde está el archivo pom.xml).
Compilar el proyecto con el comando: mvn clean compile
usar metodo principal con método main, ejecuta el proyecto con: mvn exec:java -Dexec.mainClass="com.eci.pagos.Principal" 
Si quieres correr los tests, usa: mvn test
