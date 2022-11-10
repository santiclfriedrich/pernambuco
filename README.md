# pernambuco

_Descripcion del Proyecto para CoderHouse Comision 31000 BACKEND_

Ecommerce Mern-Stack (MONGODB, EXPRESS, REACT, NODEJS)

Para la configuracion del servidor utilicé Express desarrollado en NodeJS, como base de datos Atlas MongoDB, Generé las vistas en React de un proyecto anterior el cual se basa en una tienda de ropa mía.

Para correr la aplicación estando en la carpeta principal de pernambuco, desde distintas consolas tipear primero en una cd ./backend && npm start y para el frontend lo mismo, es decir cd ./frontend && npm start.

Para navegar en la pagina como administrador registré un usuario cuyos datos son:

email: admin@example.com
contraseña: 123456

También se puede crear un usuario nuevo al entrar en Sign In y luego en 'Crear una nueva cuenta'. Las contraseñas al registrarse deben ser iguales de lo contrario no se permitirá crear el usuario.

Aunque no haya agregado opciones de Administrador está verificado cuando la persona registrada es un user o admin.

Tiene varios pasos para la compra y por último decidí usar la API de PayPal para realizar compras, y tambien con tarjeta de débito o crédito.
Para realizar una simulación de compra ingresar los siguientes datos al clickear Pago por PayPal:

emailID: sb-c7cdq20547357@personal.example.com
pass: l29f?OX<

el "<" va incluido en la contraseña.

Una vez ingresado el pago se guardará en el historial de Ordenes de Compra.
