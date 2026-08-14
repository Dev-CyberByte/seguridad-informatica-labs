# Manual Técnico — Reconocimiento y Análisis de Vulnerabilidades con Nmap y Metasploit

## Qué se hizo

Manual técnico paso a paso de una auditoría de seguridad controlada sobre un objetivo de pruebas autorizado (`scanme.nmap.org`, el servidor oficial de pruebas del proyecto Nmap), documentando:

1. **Conexión segura** mediante un túnel **OpenVPN** para aislar el tráfico de la práctica.
2. **Reconocimiento** de puertos y servicios activos con `nmap -sV --script vuln`.
3. **Búsqueda de módulos** en Metasploit (`msfconsole`, `search`, filtros por tipo/CVE/plataforma).
4. **Configuración e interpretación** de un módulo (`RHOSTS`, `USERNAME`, `run`), incluyendo qué significan columnas como *Rank* y *Check*.

## 🛠️ Herramientas y conceptos

- **Nmap** — escaneo de puertos, detección de versiones y scripts de vulnerabilidades (NSE)
- **Metasploit Framework** (`msfconsole`) — búsqueda y configuración de módulos/exploits
- **OpenVPN** — túnel seguro para aislar el entorno de prueba
- Arch Linux / Kali Linux como sistema base

## Qué aprendí

Que las herramientas por sí solas no hacen el trabajo: Metasploit organiza y clasifica muy bien la información de cada servicio, pero el verdadero reto está en **interpretar esos resultados** para proponer soluciones que realmente sirvan. Ver en la práctica cómo un puerto mal configurado puede comprometer un servidor entero hizo que la teoría vista en clase cobrara sentido real.

## Consideraciones éticas y legales

- Escanear puertos, identificar vulnerabilidades o lanzar exploits contra un servidor **sin autorización explícita** constituye un delito informático en la mayoría de las jurisdicciones.
- Un escaneo agresivo o un exploit inestable puede provocar una **denegación de servicio (DoS) involuntaria**, afectando a usuarios legítimos.
- Por eso toda la práctica se limitó a un objetivo de pruebas públicamente autorizado y a un entorno de laboratorio aislado.

---
*Práctica académica realizada en equipo en la asignatura Seguridad Informática (UPVT), Unidad IV, con fines educativos.*
