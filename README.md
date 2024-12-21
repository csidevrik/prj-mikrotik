# MikroTik CLI Comandos Básicos

Este documento contiene una lista de comandos útiles para gestionar MikroTik mediante la CLI, junto con explicaciones de su funcionalidad.

## Consultar la Versión del Sistema Operativo
Para verificar la versión de RouterOS instalada en tu dispositivo:
```bash
/system resource print
```
## Configurar un Banner de Inicio
Para establecer un banner que se muestra al iniciar sesión en el router:

```bash
/system note set show-at-login=yes
/system note set note="Bienvenido al Router MikroTik. Acceso solo autorizado. Toda actividad es monitoreada."
```
Cambiar el Nombre de Host
Para asignar un nombre al router:

```bash
/system identity set name="NombreDelHost"
```