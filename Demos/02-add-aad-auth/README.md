# <a name="completed-module-add-azure-ad-authentication"></a>Módulo completado: agregar autenticación de Azure AD

La versión del proyecto en este directorio refleja cómo completar el tutorial hasta [Agregar autenticación de Azure ad](https://docs.microsoft.com/graph/training/python-tutorial?tutorial-step=3). Si usa esta versión del proyecto, deberá completar el resto del tutorial a partir de [obtener datos de calendario](https://docs.microsoft.com/graph/training/python-tutorial?tutorial-step=4).

> **Nota:** Se supone que ya ha registrado una aplicación en el portal de registro de aplicaciones, como se especifica en [registrar la aplicación en el portal](https://docs.microsoft.com/graph/training/python-tutorial?tutorial-step=2). Debe configurar esta versión del ejemplo de la siguiente manera:
>
> 1. Cambie el nombre `oauth_settings.yml.example` del archivo `oauth_settings.yml`a.
> 1. Edite `oauth_settings.yml` el archivo y realice los cambios siguientes.
>     1. Reemplace `YOUR_APP_ID_HERE` por el **identificador de aplicación** que obtuvo desde el portal de registro de aplicaciones.
>     1. Reemplace `YOUR_APP_PASSWORD_HERE` por la contraseña que obtuvo en el portal de registro de aplicaciones.