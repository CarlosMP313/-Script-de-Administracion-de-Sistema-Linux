# Script de Administración de Sistema Linux

Este es un script interactivo de administración del sistema diseñado para funcionar en Kali Linux y otros sistemas basados en Linux. El script permite realizar varias tareas de administración del sistema de manera sencilla mediante un menú interactivo con colores para facilitar la lectura y la interacción.

## Funciones Principales

1. **Actualizar el Sistema**
   - Actualiza el sistema y los paquetes instalados.
   - Usa `apt` para sistemas basados en Debian/Ubuntu y `dnf` para sistemas basados en Red Hat (como CentOS, Fedora).

2. **Gestión de Procesos**
   - Muestra procesos en ejecución con `ps`, `top` y `htop`.
   - Permite matar procesos por ID de proceso (PID) o por nombre.
   - Ejecuta comandos en segundo plano.

3. **Gestión de Servicios**
   - Muestra el estado de los servicios y permite iniciar, detener, reiniciar, habilitar o deshabilitar servicios usando `systemctl`.

4. **Administración de Usuarios y Grupos**
   - Permite crear, eliminar y modificar usuarios y grupos.
   - Cambia contraseñas de usuarios y muestra los grupos a los que pertenece un usuario.

5. **Gestión de Discos y Archivos**
   - Muestra el uso de espacio en disco con `df`.
   - Muestra el tamaño de un directorio específico con `du`.
   - Monta y desmonta particiones.

6. **Visualización de Logs y Diagnóstico**
   - Muestra los logs del sistema y mensajes del arranque con `dmesg`, `journalctl`, y `tail`.
   - Permite seguir logs de seguridad y del sistema en tiempo real.

7. **Seguridad y Permisos**
   - Cambia permisos y propietarios de archivos con `chmod` y `chown`.
   - Configura el firewall con `ufw` para permitir o denegar puertos específicos.

8. **Otros Comandos Útiles**
   - Permite reiniciar o apagar el sistema.
   - Muestra el tiempo de actividad del sistema (`uptime`).
   - Muestra el historial de comandos ejecutados.

## Requisitos

- El script está diseñado para funcionar en **Kali Linux** y otros sistemas basados en **Debian/Ubuntu** o **Red Hat**.
- Para algunas funciones, se requiere acceso de superusuario (sudo).

## Uso

1. Guarda el script como `admin_system.sh`.
2. Dale permisos de ejecución:
   ```bash
   chmod +x admin_system.sh
