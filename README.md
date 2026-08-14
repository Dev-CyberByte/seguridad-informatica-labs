# Seguridad Informática — Laboratorios de Práctica

Documentación técnica de las prácticas realizadas en la asignatura **Seguridad Informática**, dentro del programa de Ingeniería en Tecnologías de la Información — Universidad Politécnica del Valle de Toluca.

> ⚠️ **Aviso ético y legal**
> Todas las prácticas de este repositorio se realizaron en **entornos controlados y aislados** (máquinas virtuales, redes internas y túneles VPN), bajo supervisión docente y con fines exclusivamente académicos. Ningún sistema, red o persona ajena al laboratorio fue escaneado, atacado o comprometido. Este material tiene un propósito educativo y de concientización — **no debe usarse contra sistemas sin autorización explícita.**

---

## Contenido

| Práctica | Descripción |
|---|---|
| **Caso: Cómputo Forense** | Aplicación de la metodología forense (identificación, adquisición, preservación, análisis, documentación y presentación) ante un caso simulado de acceso no autorizado y eliminación de archivos. |
| **Manual técnico — Nmap y Metasploit** | Reconocimiento de red y análisis de vulnerabilidades sobre un objetivo autorizado (`scanme.nmap.org`), documentando cada comando ejecutado y su propósito. |
| **Investigación — Zphisher y CamPhish** | Análisis conceptual y demostración controlada de herramientas de phishing automatizado, con comparativa técnica y propuesta de contramedidas (MFA, políticas de privilegios mínimos). |

---

## 🛠️ Herramientas y tecnologías utilizadas

![Nmap](https://img.shields.io/badge/Nmap-4682B4?style=for-the-badge&logo=nmap&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=for-the-badge&logo=metasploit&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![OpenVPN](https://img.shields.io/badge/OpenVPN-EA7E20?style=for-the-badge&logo=openvpn&logoColor=white)

- **Escaneo y explotación:** Nmap, Metasploit Framework (`msfconsole`)
- **Análisis de tráfico:** Wireshark
- **Conectividad segura:** OpenVPN (túnel aislado hacia el objetivo de pruebas)
- **Sistemas operativos:** Arch Linux, Kali Linux
- **Metodología forense:** cadena de custodia, imagen forense bit a bit, validación por hash (MD5/SHA-256)

---

## Entorno de trabajo

Todas las prácticas se desarrollaron dentro de un **ambiente de laboratorio controlado**:

- Máquinas virtuales aisladas (Arch Linux / Kali Linux).
- Conexión mediante **túnel VPN** para separar el tráfico de prueba de la red real.
- Objetivos de prueba **públicos y autorizados** para fines de auditoría (ej. `scanme.nmap.org`, el servidor de pruebas oficial del proyecto Nmap).
- Supervisión directa del docente de la asignatura durante cada ejercicio.

---

## 👥 Colaboradores

Prácticas realizadas en equipo:

- Juan Pablo Olivares  — [github.com/Dev-CyberByte](https://github.com/Dev-CyberByte)
- Roberto Carlos Camacho
- Miguel Alejandro Loa

**Facilitador:** Ing. Héctor Abraham Fernández Martínez

---

##  Objetivo del repositorio

Servir como evidencia documentada de las prácticas de laboratorio de la Unidad 4 — *Tendencias en la Seguridad Informática*, y como referencia personal de aprendizaje en reconocimiento de redes, análisis de vulnerabilidades, cómputo forense e ingeniería social.
