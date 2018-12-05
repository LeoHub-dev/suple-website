# Lista objetivos - Proyecto Suple



* Crear pagina web

  #### La pagina web tendrá estas características: 

  1. **Registro de usuarios**

     * Registro manual

     * Registro por Facebook

     * Registro por Google

  2. **Pagina - Lista de productos/servicios**

     * Buscador de servicios & productos

     * Filtro por categorías

     * Calificaciones de cada producto

  3. **Pagina - Producto X**

     * Precio

     * Cantidad

     * Nombre

     * Comprar

     * Recomendados

     * Agregar lista de deseos

  4. **Pagina - Dashboard de usuario**

     * Lista de compras realizadas

     * Saldo actual en X moneda

     * Lista de referidos
     * Código & Link para Referir

     * Registro ganancias obtenidas por comisión

     * Registro ganancias obtenidas por referidos

     * Recarga de saldo

     * Modificación de datos/perfil

     * Lista de deseos

     * Lista de requisitos validados

     * Saldo Retenido (En caso de no cumplir requisitos)

  5. **Pagina - Panel Administrativo**

     * Compras Realizadas

     * Notificaciones

     * Control de usuarios

     * Control de servicios/productos

     * Configuración de % de cada nivel

     * Configuración de N de niveles

     * Configuración de % que obtendrán los referidos

     * Configuración de % para el comprador

     * Registro de empresas (Para las Api)

     * Reportes Diarios, Semanales, Mensuales
     * Configuración de monedas

* Crear Aplicación Móvil (Mismas características que la Web)



# Proceso que debería realizar un usuario común: 



1. Usuario ingresa a la pagina o aplicación móvil mediante el link de referido ó por buscador de google.

2. Usuario entra al área de registro y ingresa sus datos.

3. Usuario recibe un correo y valida su cuenta.

4. Usuario es enviado a su Dashboard y se le indica que tiene 0 saldo.

5. Se le ofrece la opción / se le indica que para usar los servicios necesita saldo.

6. Usuario selecciona "Recargar Saldo", se le indica las opciones que hay para recargar, que serian "Cheques" o "Transferencia".

7. Se le indica los datos con los que debe realizar la recarga.

8. Usuario realiza la transferencia. Es verificada y su saldo es aumentado.

9. Usuario busca el servicio que desea en la pagina, lo agrega a su carro de compras, y finaliza la compra.

   ***(Todos los porcentajes serán posibles de modificar desde el sistema. Los indicados aquí es en base de ejemplo)***

   * Aquí el usuario obtiene el 50% del 5% de su compra. (Osea si gasta 100 pesos, se obtiene el 5% del total -100 pesos- que serian 5 pesos. Y de esos 5 pesos, obtendrá el 50%, que serian 2.5 pesos)
   * Los otros 2.5 pesos (El 50% faltante de los 5 pesos totales). 45% será dividido con las 9 personas encima de el (Mientras estos usuarios hayan calificado para obtener esa bonificación). 5%*9 = 45%.
   * El 5% faltante se le dará al referido del usuario.

10. Los datos de la compra son enviados al proveedor/empresa.

11. El usuario recibe el servicio que pago.
