---
layout: default
title: Usuarios
nav_order: 4
parent: Admin
---

# Usuarios
{: .no_toc }

En esta sección podras ver y administrar a los usuarios de la plataforma.
{: .fs-6 .fw-300 }

[![Captura de pantalla de Usuarios en SIU](../../assets/images/usuarios-index.png)](../../assets/images/usuarios-index.png){:target="_blank"}


## Tabla de contenido
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Información de la tabla

- **Usuario**
  - El nombre de usuario con el que inicia sesion el usuario.
  - Al hacer click sobre el nombre de usuario se abrira un modal para asignar un Grupo y un Canal al usuario.

- **Grupo-Canal**
  - El nombre del grupo y canal al que esta ligado el usuario.
  - El Grupo esta relacionado con los grupos de seguridad del modulo [Grupos]({% link admin/grupos.md %}).

- **Super Usuario**
  - Indica si el usuario cuenta con permisos de super usuario.

- **Email**
  - El correo electronico del usuario.

- **Nombre**
  - El nombre del usuario.

- **Apellidos**
  - Los apellidos del usuario.

- **Ultima Conexión**
  - La fecha y hora de la ultima vez que el usuario inicio sesion en la plataforma.
  - Si el usuario nunca ha iniciado sesion en la plataforma, este campo estara vacio.
  - Tal como se indica en la sección [Limpiar login]({% link admin/limpiar_lastlogin.md %}), si este valor esta vacio cualquier persona puede [asignar una nueva contraseña]({% link admin/limpiar_lastlogin.md %}#asignar-nueva-contraseña-a-usuario-sin-last_login) al usuario.

- **Acciones**
  - **_Campus_**
    - Muestra y permite configurar los campus a los que tiene acceso el usuario.
  - **_Activar/Desactivar_**
    - Permite activar o desactivar el usuario.

## Asignar grupo de seguridad y canal de venta a usuario

Para realizar esta accion, bastara con hacer click sobre el nombre de usuario en la tabla de usuarios. Al hacer esto, se abrira un modal en donde se podra seleccionar el grupo de seguridad y el canal de venta al que se desea asignar al usuario.

[![Captura de pantalla del modal para asignar grupo y canal a un usuario en la pantalla de Usuarios de SIU](../../assets/images/usuarios-modal-canalgrupo.png)](../../assets/images/usuarios-modal-canalgrupo.png){:target="_blank"}

1. **Grupo**
  - Se debera seleccionar el grupo de seguridad al que se desea asignar al usuario.
  - El grupo de seguridad es el que dicta los permisos que un usuario tendra dentro de la plataforma.

2. **Id canal**
  - Se debera seleccionar el canal de ventas al que se desea asignar al usuario.
  - El canal de ventas es el que indica, entre otras cosas, el acceso a los campus, programas, paquetes y mas para la creacion de solicitudes por parte del usuario.

## Asignar campus a usuario

Para realizar esta accion, bastara con hacer click sobre el boton [![](../../assets/images/usuarios-campus-button.png)](../../assets/images/usuarios-campus-button.png){:target="_blank"} de la fila del usuario que se desea modificar en la tabla de usuarios. Al hacer esto, se abrira un modal en donde se podra seleccionar los campus a los que se desea asignar al usuario.

[![Captura de pantalla del modal para asignar campus a un usuario en la pantalla de Usuarios de SIU](../../assets/images/usuarios-modal-campus.png)](../../assets/images/usuarios-modal-campus.png){:target="_blank"}

1. **Campus**
  - Se deberan activar los switch de los campus que se deseen vincular al usuario.
  - La configuracion de campus es utilizada durante la creacion de solicitudes por parte del usuario. Es importante que el campus se encuentre correctamente configurado para poder generar solicitudes de admision para este.