# Proyecto **MERN** De Administrador De pacientes de Veterinaria
### MongoDB - Express - React - Node.js

Cada veterinario puede crear su propia cuenta privada, la cual se almacena en **MongoDB** hasheando su contraseña, dandole mayor seguridad al usuario.
Se utiliza **nodemailer**, como transporte para usar el **SMTP** de MailTrap en el entorno de desarrollo con el cual se envian las instrucciones y la redireccion a crear la nueva contraseña cuando se hace uso de "Olvide password".
Cada Veterinario puede crear, eliminar y editar sus propios pacientes que almacene.
Se utilizan Variables de entorno para ocultar informacion delicada.
Se hace uso de **JsonWebToken** para verificar y obtener el perfil del Veterinario
...

### Preview: https://administrador-de-pacientes-mern-frontend.vercel.app/
### Cuenta de prueba para ingresar: 
Usuario: prueba@prueba.com  |  Contraseña: password