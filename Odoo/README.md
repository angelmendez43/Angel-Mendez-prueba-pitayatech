Desarrolle las propuestas que brinden solución a los siguientes requerimientos proporcionados por gerencia. (Puede proponer la compra de módulos y su implementación, estimar tiempo de desarrollo u ofrecer soluciones alternativas de ser necesario).

1. La gerencia de mercadeo necesita generar un reporte diario con las visitas de clientes a tiendas, este reporte debe contener:
Cantidad de compras realizadas en el día, medio por el cual se enteraron de la empresa, comentarios del cliente.

    a. como primer paso debemos instalar el modulo de gestion de clientes, ventas.
    b. Podemos agregar un campo en el formulario del cliente donde se le pregunte como se enteraron de la empresa.
    c. utilizamos el modulo de ventas para registar las compras realizadas por los clientes.
    d. los comentarios de los clientes podemos utilizar el campo de notas o un campo personalizado.
    e. crear un informe personalizado, tener encuenta tener instalado las herramientas de Qweb para poder descargar y ver nuestros reportes.
    f. podemos configurar una tarea programada en odoo para generar automaticamete el informe diario.

    Los tiempos de desrrollo dependara de la complejidad de requistos adionales que sean necesarios, podriamos dar un estimado de 15 a 20 horas. 

 2.	Como parte del servicio post-venta la gerencia de mercadeo, desea enviar a todos sus clientes una encuesta de satisfacción una vez que la venta se encuentra facturada.
   
    a. tener instalado el modulo de ventas y de encuesta.
    b. en el modulo de encuesta crear una encuesta de satisfacción.
    c. creacion de flujo de trabajo con workflow personalizado en odoo para el envio automatizado despues de generada la venta 
    d.podemos utilizar las plantillas de correo electronico de odoo  para diseñar mensajes que acompañe de a la encuesta, podriamos un saludo al cliente, agradecimiento en la compra etc.
    e.Configuarar tarea para mandar las encuestas a los clientes cuando la venta este concluida.

      Los tiempos de desrrollo dependara de la complejidad de requistos adionales que sean necesarios, podriamos dar un estimado de 15 a 20 horas.

3.	La empresa “Los 3 Amigos”, cuenta con una aplicación externa a Odoo quemaneja la logística de sus envíos y recepciones. Dicha aplicación se encuentra desarrollada en Python y alojada en Amazon.
Actualmente, para registrar los costos de gasolina, mantenimiento y depreciación de vehículos en Odoo se genera un reporte de excel desde esta aplicación y se registran manualmente uno por uno.
Se desea automatizar la carga de esta información a Odoo para evitar el trabajo manual.


    a. necesitariamos una API para la comunicacion con odoo
    b. crear un modulo donde se conecten la API con odoo
    c. crear campos en el modelo para almacenar los datos, como costos de gasolina , mantemimiento etc.
    d. instalar el modulo cron para ejecutar automaticamente la solicitd de los datos de la API
    e. Utilizar las funciones de creacion y actualización de los registros de odoo para poder almacenar los costos de manera automatica. 

     Los tiempos de desrrollo dependara de la complejidad de requistos adionales que sean necesarios, podriamos dar un estimado de 25 a 35 horas.