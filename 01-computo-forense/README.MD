# Caso: Cómputo Forense

##  Qué se hizo

Análisis de un caso simulado en el que una empresa detecta la eliminación de archivos importantes y sospecha de un acceso no autorizado a uno de sus equipos. Se documentó, paso a paso, la intervención de un especialista en cómputo forense aplicando las **cinco etapas del proceso forense**:

1. **Identificación y aseguramiento inicial** — aislar el equipo comprometido sin alterar la evidencia.
2. **Adquisición** — copia bit a bit del disco (imagen forense) y captura de memoria RAM.
3. **Preservación** — resguardo del disco original, trabajo únicamente sobre la copia.
4. **Análisis** — revisión de logs, metadatos, tráfico de red e indicadores de compromiso (IoC).
5. **Documentación y presentación** — informe técnico con cadena de custodia y hallazgos.

## 🛠️ Herramientas y conceptos

- Imagen forense / *write blocker* (ej. FTK Imager, EnCase, `dd`/`dcfldd`)
- Validación de integridad mediante hash **MD5 / SHA-256**
- Cadena de custodia
- Análisis de logs de sistema y de acceso remoto (RDP, VPN, SSH)
- Recuperación de archivos eliminados (*data carving*)

## Qué aprendí

Que la parte técnica (sacar una imagen del disco, revisar logs) es solo la mitad del trabajo — la otra mitad, igual de importante, es la **disciplina metodológica**: nunca tocar el equipo original, documentar cada paso con hora y responsable, y mantener la cadena de custodia intacta. Sin eso, toda la evidencia técnica pierde valor.

## Consideraciones éticas y legales

- Si no se sigue una cadena de custodia adecuada, la evidencia puede ser **impugnada y rechazada** en un proceso judicial o laboral.
- Trabajar directamente sobre el equipo original (en vez de una copia forense) puede alterar metadatos y contaminar la evidencia de forma irreversible.
- Un mal manejo de la evidencia no solo afecta el caso técnico — también deja a la organización expuesta legal y reputacionalmente.

---
*Práctica académica realizada en la asignatura Seguridad Informática (UPVT), Unidad IV, con fines educativos.*
