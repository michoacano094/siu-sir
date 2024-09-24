---
layout: default
title: Limpiar login
nav_order: 3
parent: Admin
---

# Limpiar login
{: .no_toc }

{: .warning }
Antes de realizar este proceso ten en cuenta que cualquiera con el nombre de usuario puede asignar una nueva contraseña si el valor de last_login esta vacio.

En esta sección podras eliminar la fecha de last_login de un usuario para que la siguiente vez que inicie sesión se le pida que ingrese una nueva contraseña.
{: .fs-6 .fw-300 }

[![Captura de pantalla del la sección Limpiar last_login de SIU](../../assets/images/limpiarlastlogin-index.jpeg)](../../assets/images/limpiarlastlogin-index.jpeg){:target="_blank"}

## Tabla de contenido
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Limpiar valor last_login a usuario

Esta pantalla cuenta con 2 filtros disponibles para encontrar al usuario al que se desea eliminar el valor de last_login.

[![Captura de pantalla de filtros de la sección Limpiar login de SIU](../../assets/images/limpiarlastlogin-filters.png)](../../assets/images/limpiarlastlogin-filters.png){:target="_blank"}

1.  **Buscar por usuario**
    -   Este filtro permite buscar al usuario por su nombre de usuario (_correo electronico en el caso de alumnos_).
2.  **Buscar por matricula**
    -   Este filtro permite buscar al usuario por su matricula.

Una vez que se ubica el usuario, bastara con hacer click al boton [![Captura de pantalla de boton limpiar de la sección Limpiar login de SIU](../../assets/images/limpiarlastlogin-clear-button.png)](../../assets/images/limpiarlastlogin-clear-button.png){:target="_blank"} y esperar a que la plataforma termine de ejecutar el proceso. Al finalizar, se deberia poder ver al usuario en la tabla pero con la columna Last login sin un valor establecido.

[![Captura de pantalla de lista de usuarios de la sección Limpiar login de SIU](../../assets/images/limpiarlastlogin-cleaned-user.jpeg)](../../assets/images/limpiarlastlogin-cleaned-user.jpeg){:target="_blank"}

## Asignar nueva contraseña a usuario sin last_login

Una vez completado el proceso de [Limpiar valor last_login a usuario](#limpiar-valor-last_login-a-usuario), sera posible asignar una nueva contraseña al usuario. Para realizar dicha accion bastara con ir a la pagina de inicio de sesión del sistema e ingresar el usuario que no tiene un valor en last_login. Al hacer esto, se abrira un modal en donde se debera ingresar una nueva contraseña para el usuario.

[![Captura de pantalla del login de SIU cuando un usuario no tiene un valor en last_login](../../assets/images/limpiarlastlogin-new-password.jpeg)](../../assets/images/limpiarlastlogin-new-password.jpeg){:target="_blank"}
