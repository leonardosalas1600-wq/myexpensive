# myexpensive
# MyExpense - Writeup (Pentesting Lab)

## Descripción
Resolución de máquina vulnerable en entorno de laboratorio, enfocada en reconocimiento, explotación y obtención de acceso.

## Herramientas utilizadas
- Nmap
- Navegador web
- Python (básico)

## Fase de reconocimiento
Se realizó escaneo de puertos con Nmap:
nmap -sCV -p- <IP>

Se identificaron servicios web activos.

## Explotación
Se identificó una vulnerabilidad XSS en la aplicación web, que permitió la captura de cookies de sesión.

Mediante el uso de scripts, se logró reutilizar las cookies para acceder a cuentas de usuario (manager).

## Resultado
Acceso a cuentas privilegiadas y manipulación de funciones dentro de la aplicación.

## Aprendizaje
- Importancia de validar entradas en aplicaciones web
- Riesgos de XSS en sesiones activas
- Uso de herramientas de reconocimiento como Nmap
