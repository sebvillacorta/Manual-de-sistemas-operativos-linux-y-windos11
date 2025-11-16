<dir center >
  
# Manual-de-sistemas-operativos-linux-y-windos11
  
</dir>

### 🧭 1. Introducción

Un **Sistema Operativo (SO)** es el software que **administra los recursos** del hardware y **permite la interacción** entre el usuario y el sistema.

> 🎯 Objetivo: Comprender la estructura, funciones, tipos y administración básica de sistemas operativos (Windows, Linux, macOS).
> 

---

### 🧩 2. Funciones Principales del SO

| Función | Descripción |
| --- | --- |
| **Gestión de Procesos** | Controla la ejecución de programas y multitarea. |
| **Gestión de Memoria** | Asigna y libera memoria para los procesos. |
| **Gestión de Archivos** | Controla lectura, escritura y permisos. |
| **Gestión de Dispositivos** | Controla hardware mediante drivers. |
| **Interfaz de Usuario** | CLI (Terminal) o GUI (Gráfica). |

---

### 🧱 3. Estructura del Sistema Operativo

1. **Kernel:** Núcleo central que interactúa con el hardware.
2. **Shell:** Intérprete de comandos (CLI).
3. **Sistema de Archivos:** Organización jerárquica (/, /home, C:, etc.).
4. **Servicios y Daemons:** Programas que se ejecutan en segundo plano.
5. **Interfaz de Usuario:** Entorno gráfico o terminal.

---

### 🐧 4. Tipos de Sistemas Operativos

| Tipo | Ejemplo | Uso Principal |
| --- | --- | --- |
| **Monotarea** | MS-DOS | Sistemas antiguos |
| **Multitarea** | Linux, Windows | Trabajo concurrente |
| **Tiempo Real (RTOS)** | QNX, VxWorks | Robots, sistemas industriales |
| **Distribuidos** | UNIX Clusters | Centros de datos |
| **Embebidos** | Android, RPi OS | Dispositivos pequeños |

---

### 🖥️ 5. Estructura del Sistema de Archivos

### 🐧 En Linux:

```
/ (raíz)
├── bin/      → Binarios del sistema
├── etc/      → Configuraciones
├── home/     → Usuarios
├── var/      → Logs, cachés
├── dev/      → Dispositivos
└── tmp/      → Archivos temporales

```

### 🪟 En Windows:

```
C:\
├── Program Files\
├── Users\
├── Windows\
└── Temp\

```

---

### ⚙️ 6. Comandos Esenciales

**Linux:**

```bash
pwd        # Mostrar ruta actual
ls -l      # Listar archivos detalladamente
cd /home   # Cambiar de directorio
cp, mv, rm # Copiar, mover, borrar
chmod, chown # Permisos
top, htop  # Ver procesos activos

```

**Windows (CMD o PowerShell):**

```powershell
dir
cd ..
copy
move
del
tasklist
get-process

```

---

### 🔐 7. Procesos, Memoria y Seguridad

- Cada programa es un **proceso**, identificado por un **PID**.
- Linux usa el comando `ps aux` o `htop` para verlos.
- Windows usa el **Administrador de Tareas**.
- La seguridad se basa en **permisos**, **usuarios** y **roles administrativos** (`sudo` en Linux, `Administrator` en Windows).

---

### 🧠 8. Virtualización y Dual Boot

- **Dual Boot:** Instalar dos SO (ej. Linux + Windows).
- **Virtualización:** Crear máquinas virtuales con VirtualBox o KVM.
    
    ```bash
    sudo apt install virtualbox
    
    ```
    
    Ideal para prácticas sin afectar tu sistema principal.
    

---

### 🧰 9. Ejercicio Práctico

1. Instala una **máquina virtual Linux** (Ubuntu o Fedora).
2. Usa comandos básicos para navegar, crear archivos y usuarios.
3. Identifica el kernel:
    
    ```bash
    uname -r
    
    ```
    
4. Crea una tabla comparativa entre Linux y Windows (rendimiento, permisos, estabilidad, seguridad).

---

### 📚 10. Recursos Recomendados

- 📘 *Operating System Concepts* – Silberschatz, Galvin & Gagne
- 🐧 *Linux Bible* – Christopher Negus
- 📺 YouTube: DorianTech, Nestor Serrano, Platzi Linux Fundamentals
- 💻 Simuladores: https://copy.sh/v86/

---

## ✅ RESUMEN GENERAL

| Concepto | Manual 1: Arquitectura | Manual 2: SO |
| --- | --- | --- |
| Nivel | Básico / Técnico | Básico – Intermedio |
| Enfoque | Hardware y rendimiento físico | Administración y control lógico |
| Práctica | Desarmar, identificar, limpiar | Instalar, ejecutar, usar terminal |
| Herramientas | Multímetro, aire comprimido | VirtualBox, Bash, PowerShell |
