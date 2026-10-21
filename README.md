# GTS Reboot Manager

Herramienta para reiniciar remotamente dispositivos GTS mediante red LAN, con soporte para programación horaria, reintentos automáticos cuando el equipo está ocupado y registro de eventos en un log.

![Python](https://img.shields.io/badge/Python-3.7%2B-blue)
![Tkinter](https://img.shields.io/badge/UI-Tkinter-green)
![Status](https://img.shields.io/badge/Status-Production-success)

- [Interfaz y funcionalidades](Funcionalidades.md)

![Vista principal](https://github.com/user-attachments/assets/8e715112-8c88-4897-a43e-02b844e7b9b1)

## Puesta en marcha

**Requisitos**

- Python 3.7 o superior.
- Acceso de red a los dispositivos GTS.
- El archivo `ips.txt` con las direcciones de los equipos.

## Características

- Interfaz gráfica.
- Reinicio inmediato de varios dispositivos.
- Reinicio automático programado a una hora definida.
- Detección de host ocupado con reintentos automáticos.
- Carga dinámica de las IP desde el archivo `ips.txt`.
- Contadores de GTS reiniciados, pendientes y con error.
- Barra de progreso general en tiempo real.
- Registro detallado en el archivo `reboot_log.txt`.

## Licencia

Este proyecto está bajo la Licencia MIT.

## Autor

Alejandro Espinoza
Foxconn México
