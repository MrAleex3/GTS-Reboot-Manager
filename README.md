# GTS Reboot Manager

Herramienta para reiniciar remotamente dispositivos GTS mediante red LAN, con soporte para programación horaria, reintentos automáticos cuando el equipo está ocupado y registro de eventos en un log.

![Interfaz](https://github.com/user-attachments/assets/8e715112-8c88-4897-a43e-02b844e7b9b1)

![Contadores y barra de progreso](https://github.com/user-attachments/assets/63b3aba8-80c0-45da-9a49-fbe09765efec)

## Características

- Interfaz gráfica.
- Reinicio inmediato de varios dispositivos.
- Reinicio automático programado a una hora definida.
- Detección de host ocupado con reintentos automáticos.
- Carga dinámica de las IP desde el archivo `ips.txt`.
- Contadores de GTS reiniciados, pendientes y con error.
- Barra de progreso general en tiempo real.
- Registro detallado en el archivo `reboot_log.txt`.

## Requisitos

- Python 3.7 o superior.

## Licencia

Este proyecto está bajo la Licencia MIT.

## Autor

Alejandro Espinoza
Foxconn México
