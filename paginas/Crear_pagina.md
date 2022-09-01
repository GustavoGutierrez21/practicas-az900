# Crear una pagina Web en Wordpress
**Objetivo:** Crear una pagina web en wordpress, pero administrado desde el portal de Azure con App Service.

## Requisitos:
- Tener una cuenta en Azure con saldo.

---------------------------

## Contenido

### I. Creación de Wordpress con App Serive.

1. Entrar al [portal de Azure](https://portal.azure.com/) e iniciar sesión.

![](https://github.com/GustavoGutierrez21/practicas-az900/blob/main/imagenes/1_crear_pagina_web/inicio_sesion.png) ![](https://github.com/GustavoGutierrez21/practicas-az900/blob/main/imagenes/1_crear_pagina_web/1.png)

2. En el buscador de Azure escribir “Marketplace”.

![](https://github.com/GustavoGutierrez21/practicas-az900/blob/main/imagenes/1_crear_pagina_web/2.png)

3. Te mandara a la siguiente ventana.

![](https://github.com/GustavoGutierrez21/practicas-az900/blob/main/imagenes/1_crear_pagina_web/3.png)

4. En la búsqueda de Marketplace escribir “WordPress”

![](https://github.com/GustavoGutierrez21/practicas-az900/blob/main/imagenes/1_crear_pagina_web/4.png)

5. Seleccionar la primera opción "WordPress".

![](https://github.com/GustavoGutierrez21/practicas-az900/blob/main/imagenes/1_crear_pagina_web/5.png)

6.	Elegir el plan de “WordPress” y luego “Crear”.

![](https://github.com/GustavoGutierrez21/practicas-az900/blob/main/imagenes/1_crear_pagina_web/6.png)

Para la configuración de los datos básicos de Wordpress se divide el las siguientes categorias:
- Detalles del proyecto
- Detalles de instancia
#### Detalles del proyecto
En el caso de mi ejemplo quedará de esta forma:
| Elemento | Contenido | 
| -- |-- |
| Suscripción | Azure for Student | 
| Grupo de recursos | practica1-crear-una-pagina-web |
| Región | South Central US |

7. Al Entrar a la  configuración, primero elegir algún tipo de suscripción disponible (en mi caso Azure for Student) y crear un nuevo grupo de recursos dando clic en “Crear nuevo”.

![](https://github.com/GustavoGutierrez21/practicas-az900/blob/main/imagenes/1_crear_pagina_web/7.png)

Nota: en caso de tener ya un grupo de recurso que se usará para la página web solo seleccionarlo y saltarse al paso 9.