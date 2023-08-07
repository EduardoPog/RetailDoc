Actualmente la API se divide en 7 diferentes módulos:

# Auth

Aquí se encuentra el endpoint para realizar el login, *este es el único endpoint en todo el proyecto que no neesita los headers de autenticaicón*, además de que se haya la dependencia que se ejecuta en cada endpoint para comprobar la identidad de la persona que desea utilizar un endpoint.

# Categories

Estos endpoints están relacionados a la consulta, creación, modificación y eliminación de agrupaciones, así como sus respectivos sub-categorías/grupos, además de que está la posibilidad de asignar y remover plazas a los grupos.

# Contact

Consta de un único endpoint el cuál es utilizado para poder enviar un correo de reporte hacía el equipo de mantenimiento.

# Dashboard

Contiene el endpoint que se utiliza para extraer la información básica que se desplegará en la página de inicio.

# Goals

Son los endpoints relacionados a la consulta y modificacion de los objetivos anuales por plazas.

# Misc

Estos endpoints no están incluidos dentro de la API, son consultas que se encontraron dentro de la versión antigua del sitio web de Retail, pero no tienen un uso en esta API.

# Users

Endpoints para obtener los usuarios que pueden subir archivos a la plataforma, desde aquí se pueden modificar sus permisos.
