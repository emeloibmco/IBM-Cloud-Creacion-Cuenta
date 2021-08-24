# IBM Cloud - Creación de Cuenta ☁

IBM Cloud® tiene tres tipos de cuentas: Lite, Pay-As-You-Go y Suscripción. Obtienes una cuenta Lite gratuita tan pronto como te registras. Pago por uso y Suscripción son opciones de cuenta facturables y cada una ofrece características diferentes. 

La presente guia está enfocada en orientar a nuestros clientes para crear su propia cuenta ![image](https://user-images.githubusercontent.com/88363223/128292556-a1a1c419-3efb-4751-9ec7-daa69ec7c1d3.png) para disfrutar de los servicios que ofrece IBM Cloud de forma gratuita y sin uso de tarjeta de crédito. 

Regístrese para obtener una cuenta Lite para comenzar a crear sus aplicaciones y explorar servicios con planes Lite gratuitos seleccionados, que se muestran con una etiqueta ![image](https://user-images.githubusercontent.com/88363223/128293121-ef9319e2-d329-437f-941d-eb98db6d2f47.png) en la consola de IBM Cloud. Su cuenta Lite no caduca y no se requiere su tarjeta de crédito.

Tiene acceso a un único grupo de recursos creado para usted y denominado Predeterminado. Todas las instancias de su servicio gestionadas por IBM Cloud Identity and Access Management (IAM) se agregan automáticamente a este grupo de recursos. Puede actualizar el nombre de este grupo de recursos en cualquier momento. Consulte Cambiar el nombre de un grupo de recursos para conocer los pasos detallados.

<br />

## Índice  📰
1. [Información de la cuenta](#Información-de-la-cuenta)
2. [Verificar correo](#verificar-correo)
3. [Documentar informacion personal](#Documentar-informacion-personal)
4. [Crear cuenta](#Crear-cuenta)
5. [Doble factor de autenticación](#Doble-factor-de-autenticación)
6. [Referencias](#Referencias)
7. [Autores](#Autores)
<br />

## Información de la cuenta
* Ingresar al portal <a href="https://cloud.ibm.com/"> IBM Cloud</a>.
* Para crear una nueva cuenta, damos click en la opción <a href="https://cloud.ibm.com/registration"> Crear una cuenta</a>.

<p align="center"><img width="500" src="https://user-images.githubusercontent.com/88363223/128416205-f3273554-9347-4e44-a3f9-af797519dedb.png"></p>

* En los parametros de creación de la cuenta,  iniciamos por documentar la ```Información de la cuenta```.  Digitamos una dirección de correo electrónico y una contraseña que cumpla con los parámetros establecidos en el portal.

<p align="center"><img width="500" src="https://user-images.githubusercontent.com/88363223/128297098-aecbfe56-42fc-4c6f-9f41-b4413bcb2b76.png"></p>

<br />


## Verificar correo

* Un correo similar al correo adjunto en la image será enviado a la cuenta de correo consignada en el paso anterior. 

<p align="center"><img width="500" src="https://user-images.githubusercontent.com/88363223/128297326-2f2d75ae-54d0-4e56-aaa1-1f66d0c7cc1c.png"></p>

* Un correo similar al correo adjunto en la image será enviado a la cuenta de correo consignada en el paso anterior. 

<p align="center"><img width="500" src="https://user-images.githubusercontent.com/88363223/128296985-1712a2f1-5838-4c79-8314-a41db1e6ea79.png"></p>

* Un correo similar al correo adjunto en la image será enviado a la cuenta de correo consignada en el paso anterior. 

<p align="center"><img width="500" src="https://user-images.githubusercontent.com/88363223/128297367-812411f2-c053-4e4f-aa97-a24754982c3d.png"></p>

<br />


## Documentar informacion personal

<p align="center"><img width="500" src="https://user-images.githubusercontent.com/88363223/128297418-6e2f25e4-2272-4158-ab70-f0377e1349e9.png"></p>

<br />

## Crear cuenta

<p align="center"><img width="500" src="https://user-images.githubusercontent.com/88363223/128297485-8c25fecb-2d0f-401e-b71f-0c9bc36d3228.png"></p>

<br />

<p align="center"><img width="500" src="https://user-images.githubusercontent.com/88363223/128297708-06a0aa0d-5cb1-4ae0-9a72-54acd2c3d7bd.png"></p>

<br />

## Doble factor de autenticación
Como propietario o administrador de una cuenta de *IBM Cloud*®, puede optar por solicitar la autenticación multifactor (MFA) para cada usuario de la cuenta o solo para los usuarios con IBMid que no utilizan el inicio de sesión único (SSO).

Para aplicar el doble factor de autenticación en su cuenta en *IBM Cloud*, realice lo siguiente:
<br />

1. Inicie sesión en el portal de *IBM Cloud*.
<br />

2. En la barra superior del ```Panel de control/Dashboard``` de click en la pestaña ```Gestionar/Manage``` ➡ ```Acceso (IAM)/Access (IAM)```.
<br />

3. Seleccione la opción ```Valores/Settings``` ubicada en el menú lateral izquierdo.
<br />

4. Diríjase a la sección de ```Autenticación/Authentication``` y visualice la opción ```Autenticación de multifactores (MFA)/Multifactor authentication (MFA)```. Luego de click en el botón ```Editar/Edit```.
<br />

5. Seleccione el tipo de MFA que desea utilizar para habilitar la cuenta. En este caso se tienen 3 opciones:
    * ```Ninguna/None```: no se aplica ningún tipo de MFA.
    
    * ```MFA para usuarios con un IBMid/MFA for users with an IBMid```:  solicite a los usuarios que se autentiquen mediante un IBMid, una contraseña y un código de acceso de un         solo uso basado en el tiempo (time-based one-time passcode - TOTP). Puede habilitar esta opción para todos los usuarios o usuarios no federados.
    
    * ```MFA para todos los usuarios (IBMid & IdPs soportados)/MFA for all users (IBMid & supported IdPs)```: solicite a los usuarios que se autentiquen mediante uno de los            siguientes factores de MFA (esta opción se aplica a los usuarios que utilizan un IBMid o un proveedor de identidad externo (IdP)):
    
       * ```MFA basado en correo electrónico/Email-based MFA```: los usuarios se autentican mediante un código de seguridad que se envía en un correo electrónico.
       
       * ```TOTP MFA```: los usuarios se autentican mediante un un código de acceso de un solo uso (TOTP).
       
       * ```U2F MFA```: los usuarios se autentican mediante el uso de una clave de seguridad física basada en hardware que genera un código numérico de seis dígitos. Basado en el          estándar FIDO U2F, este factor ofrece el más alto nivel de seguridad.

    Para este caso seleccione la opción ```MFA para usuarios con un IBMid/MFA for users with an IBMid``` ➡ ```Todos los usuarios/All users``` y posteriormente, habilite la           casilla de confirmación.
    
<br />

6. De click en el botón ```Actualizar/Update``` para aplicar los cambios.
<br />

<p align="center"><img width="900" src="https://github.com/emeloibmco/IBM-Cloud-Creacion-Cuenta/blob/main/Images/1_Activacion_MFA.gif"></p>
<br />

7. Cierre la sesión para realizar la prueba del MFA.
<br />

8. Inicie sesión con su cuenta de *IBM Cloud* y espere mientras carga la ventana.
<br />

<p align="center"><img width="900" src="https://github.com/emeloibmco/IBM-Cloud-Creacion-Cuenta/blob/main/Images/2_InicioSesion.gif"></p>
<br />

9. Posteriormente, debe ingresar un código que es enviado a su correo electrónico y presionar el botón ```Verificar/Verify```. Cuando cargue la ventana podrá observar un anuncio que le indica que ahora la conexión es más segura, de click en el botón ```Empezar/Get started```. Luego, le aparecerá una ventana que indica que debe usar una app como autenticador. Seleccione la opción mediante ```Configuración/Setup```, descargue en su teléfono la aplicación ```IBM Verify``` y de click en el botón ```Siguiente: Conectar a su autenticador/Next: Connect to your authenticator```.
<br />

<p align="center"><img width="900" src="https://github.com/emeloibmco/IBM-Cloud-Creacion-Cuenta/blob/main/Images/3_CodigoCorreo.gif"></p>
<br />

10. Debe agregar el autenticador de su teléfono para acceder a la cuenta. Para ello, en la aplicación descargada de su teléfono, escanee el código QR y de click en el botón ```Siguiente: Pruebe su autenticador/Next: Test your authenticator```. Ingrese el código que se muestra en su teléfono y de click en ```Siguiente: verificar/Next: verify```. Cuando complete este paso con éxito presione ```Hecho/Done```. En su teléfono deberá aparecer el correo de cuenta de *IBM Cloud*.
<br />

11. Ingrese el nuevo código de verificación que se muestre en su teléfono y de click en el botón ```Verificar/Verify```. Al final el proceso podrá visualizar el panel del control de portal y habrá accedido de forma correcta a su cuenta.
<br />

<p align="center"><img width="900" src="https://github.com/emeloibmco/IBM-Cloud-Creacion-Cuenta/blob/main/Images/4_CodigosActivacion.gif"></p>
<br />

12. Si desea desactivar el MFA realice lo siguiente: ```Gestionar/Manage``` ➡ ```Acceso (IAM)/Access (IAM)``` ➡ ```Valores/Settings``` ➡ ```Autenticación/Authentication``` ➡ ```Autenticación de multifactores (MFA)/Multifactor authentication (MFA)``` ➡ ```Editar/Edit``` ➡ ```Ninguna/None``` ➡ ```Actualizar/Update```.
<br />

<p align="center"><img width="900" src="https://github.com/emeloibmco/IBM-Cloud-Creacion-Cuenta/blob/main/Images/5_Desactivacion_MFA.gif"></p>
<br />

## Referencias
* <a href="https://cloud.ibm.com/docs/account?topic=account-account-getting-started">Setting up your IBM Cloud account</a>
* <a href="https://cloud.ibm.com/docs/account?topic=account-enablemfa">Enabling MFA for your account</a>
<br />

## Autores
Equipo *IBM Cloud Tech Sales Colombia*.

