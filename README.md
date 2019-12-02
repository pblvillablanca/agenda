# Agenda

1. Instrucciones versión Node

para crear la base de datos entra al REPL mongo:

despues inserta el siguiente comando:

use agenda_db

siguiente a eso inserta este comando:

db.usuarios.insertMany([{ email: 'demo@mail.com', user: "demo", password: "123456"}, { email: 'pablo@mail.com', user: "pablo", password: "123456"}])

luego ejecuta en la carpeta server:

node index.js

Saldra un mensaje indicand server is listening on port 3000, ingresa la siguiente direccion en el navegador:localhost:3000/index.html
