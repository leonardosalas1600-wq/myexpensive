# MyExpense - Writeup (Pentesting Lab)

> Nota: Este ejercicio fue realizado en un entorno de laboratorio.

---

##  Descripción
Resolución de una máquina vulnerable enfocada en reconocimiento, análisis y explotación de vulnerabilidades web para la obtención de acceso a cuentas.

---

##  Herramientas utilizadas
- Nmap  
- Navegador web  
- Python (básico)  

---

## Fase de reconocimiento
Se realizó un escaneo completo de puertos utilizando Nmap:

```bash
nmap -sCV -p- <IP>
