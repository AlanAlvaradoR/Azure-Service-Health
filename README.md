# Azure-Service-Health
Creación de alertas por interrupciones del servicio de Azure por medio de Service Health

![Logo de Service Health](https://github.com/AlanAlvaradoR/Azure-Service-Health/blob/main/imagenes/servicehealth.png)

## Requisitos

- Cuenta de [Azure](https://portal.azure.com/) con suscripción activa
- Computadora con Windows, Linux o MacOs

---------------------------------------------------------

## Pasos

1. Se inicia sesión en la página de [Azure](https://portal.azure.com/)

2. Se busca "Service Health" en el buscador superior y se da enter

3. Ya dentro, en el apartado izquierdo de "Problemas de servicio" se da click y después de entra en la opción de "Añadir alerta de Service Health"

4. En el apartado siguiente, se selecciona la suscripción, los servicios y en qué región se enfocará la alerta. Más abajo se selecciona el tipo de evento del que se busca alertar.

5. Más abajo en el apartado de acciones, se da click en "seleccionar grupo de acciones".

6. En el menú desplegable derecho se deberá seleccionar el grupo de acciones que se requiera, en caso de no contar con uno o si se desea crear uno nuevo, dar click en "crear grupo de acciones" y continuar con el siguiente paso. Si ya se cuenta con el grupo de acciones necesario, saltar al paso 11.

7. En el apartado de datos básicos es necesario colocar la suscripción y el grupo de recursos al que pertenecerá. Más abajo se le coloca un nombre la grupo de acciones y un nombre para mostrar.

8. En el apartado de notificaciones, se requiere colocar un tipo de notificación (puede ser por e-mail, SMS, etc.) y se le debe colocar un nombre. Se desplegará un menú derecho, n el cual se debe especificar por cuál medio se contactará y la dirección o número de telefono (según sea el caso). Una vez especificado, se da click en el botón inferior del menú derecho "Aceptar".

9. En el apartado de acciones se pueden especificar acciones de Logic Apps, functions, centro de eventos, etc. que se ejecuten a la par de la alerta.

10. Una vez terminada la configuración, se da en revisar y crear, depués de la verificación, presionar "crear".

11. Si se desea probar el grupo de acciones, se da click en su nombre y después en "grupo de acciones de prueba (versión preliminar)". En caso contrario, pasar al paso 13.

12. Se selecciona el tipo de ejemplo y se da click en "test". Se enviarán las notificaciones de prueba por el medio seleccionado.

13. Volvemos al menú de creación de una regla de alertas.

14. Ahora en el apartado de grupo de acciones se debe mostrar el grupo de acciones que seleccionamos.

15. Más abajo se debe especificar el nombre de la regla de alertas, una descripción, el grupo de recursos y seleccionar la casilla de "habilitar la regla tras la creación". Se da click en "crear regla de alertas".

