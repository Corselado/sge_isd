# DOCUMENTACION
## [PDF](./pdf/Factura_INV_2024_00002.pdf)
Iniciamos odoo y nos vamos al apartado facturación.
Al ser la primera vez simplemente seguiremos los pasos del propio asistente, comenzamos indicando la inforrmación de la compañía. En mi caso el nombre será ISD Computers.
A continuación, diseñamos la factura.
Mantendré el diseño por defecto, a excepción de añadir un logo,una imagen de fondo y los colores de encabezado y el total.
Para añadir a la factura un codigo QR, vamos a ajustes, facturación/contabilidad y marcamos la casilla Codigo QR, en el apartado "Pagos de cliente".
Para subir los datos cclientes.csv, vamos al apartado clientes, pulsamos en "Favoritos", rellenamos las casillas que nos pida Odoo con su campo, y finalmente pulsamos en importar.
Crearemos un segundo usuario con unicamente permisos de facturación, para ello vamos "Ajustes", "Usuario", "Nuevo",e indicamos en "Contabilidad : Facturación" y "Administración: Permisos de acceso".
Para crear una factura, vamos a facturación y luego a "Nuevo", rellenamos los datos, aunque la gran mayoria se rellenan del propio cliente importado. 

NOTA: si no hay ningun producto creado, tendras que crearlo con un usuario con permisos para ello.