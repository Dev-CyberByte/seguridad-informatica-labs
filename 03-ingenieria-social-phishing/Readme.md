# Ingeniería Social — Casos de Ataque y Herramientas Automatizadas de Phishing

## Qué se hizo

Investigación sobre el factor humano como el eslabón más vulnerable de la seguridad de la información, cubriendo:

- **Análisis de casos reales de ataques conocidos** (phishing, ransomware y otros ataques relevantes), estudiando cómo se ejecutaron y qué los hizo exitosos.
- **Investigación y demostración controlada** de dos herramientas automatizadas de ingeniería social: **Zphisher** (clonación de páginas de login para robo de credenciales) y **CamPhish** (captura de imágenes vía permisos del navegador).
- Comparativa técnica entre ambas herramientas: vector de ataque, tipo de dato exfiltrado, nivel de interacción requerido de la víctima.

## 🛠️ Herramientas y conceptos

- **Zphisher** / **CamPhish** — frameworks de phishing automatizado (solo con fines de investigación)
- Túneles de exposición local (*port forwarding*)
- Conceptos clave: *credential phishing*, ingeniería social, autenticación multifactor (MFA), *zero trust*

## Qué aprendí

Que la tecnología de ataque es cada vez más accesible — herramientas como estas permiten que alguien con pocos conocimientos técnicos despliegue una campaña de ingeniería social en minutos. Pero también quedó claro que estos ataques no explotan fallas en el código, sino **descuidos del comportamiento humano**. La defensa más efectiva combina controles técnicos (MFA, permisos mínimos de navegador) con educación continua del usuario.

## Consideraciones éticas y legales

- Montar un sitio falso para capturar datos de terceros **sin un contrato de auditoría o consentimiento previo** constituye un delito relacionado con fraude y robo de identidad.
- Usar estas herramientas contra amigos, familiares o compañeros "como broma" viola los principios éticos de la ciberseguridad y destruye la confianza digital.
- Toda la demostración se realizó en un entorno aislado, sin exponer datos reales de terceros ni desplegar las herramientas fuera del laboratorio.

---
*Práctica académica realizada en equipo en la asignatura Seguridad Informática (UPVT), Unidad IV, con fines educativos.*
