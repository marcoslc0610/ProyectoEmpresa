# Manual de Usuario - Sistema de Gestión de Incidencias

## Introducción
Este sistema permite gestionar reportes técnicos con tres tipos de usuarios:
- Clientes: pueden reportar problemas
- Técnicos: resuelven las incidencias
- Administradores: gestionan usuarios y asignaciones

## Primeros pasos
1. Ejecute el programa desde su terminal
2. Verá el menú principal con estas opciones:
   * 1. Inicio de sesión
   * 2. Registrarse
   * 3. Salir

## Registro de usuarios
* Seleccione la opción 2 (Registrarse)
* Ingrese:
  - Un email válido
  - Una contraseña segura
* El sistema confirmará su registro automáticamente

## Inicio de sesión
* Seleccione la opción 1 (Inicio de sesión)
* Credenciales:
  - Para clientes/tecnicos: use su email y contraseña registrados
  - Para administradores: usuario "admin" y contraseña "admin"

## Funciones por rol

### Menú de Cliente
* 1. Crear incidencia:
  - Describa el problema (asunto)
  - El sistema generará un número de incidencia
* 2. Ver historial:
  - Muestra todas sus incidencias reportadas
* 3. Consultar estado:
  - Ingrese el número de incidencia
  - Verá el estado actual (Pendiente/En proceso/Resuelta)
* 4. Salir

### Menú de Técnico
* 1. Ver incidencias asignadas
  - Lista completa de problemas asignados
* 2. Marcar como resuelta
  - Seleccione número de incidencia
  - Ingrese descripción de la solución
* 3. Cambiar estado
  - Actualice el estado según progreso
* 4. Salir

### Menú de Administrador
* 1. Gestionar usuarios:
  - Crear/eliminar/modificar cuentas
  - Cambiar roles (cliente/técnico)
* 2. Asignar incidencias:
  - Seleccione técnico e incidencia pendiente
* 3. Ver todas las incidencias
  - Listado completo del sistema
* 4. Salir

## Recomendaciones de seguridad
* Utilice contraseñas complejas
* No comparta sus credenciales
* Cierre sesión al terminar
