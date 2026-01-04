Phishing Incident Report – SOC L1
(siguiendo el enfoque de las 5 Ws)
Incident Summary

(What)
Se detectó un correo electrónico malicioso clasificado como phishing, cuyo objetivo era engañar al usuario para que interactuara con un enlace sospechoso y entregara credenciales sensibles.

Timeline of Events

(When)
La alerta fue generada automáticamente por la herramienta de seguridad de correo electrónico el [fecha del laboratorio], y escalada inmediatamente al SOC para su análisis.

Involved Entities

(Who)

Usuario afectado: Empleado interno de la organización

Atacante: Actor externo desconocido

Analista: SOC Level 1

Herramienta de detección: Sistema de seguridad de correo / SIEM

Incident Location

(Where)
El incidente se originó a través del correo electrónico corporativo, siendo entregado a la bandeja de entrada del usuario objetivo.

Incident Analysis

(Why)
El correo presentaba múltiples indicadores de phishing:

Dirección del remitente sospechosa

Enlace malicioso incrustado en el cuerpo del mensaje

Uso de ingeniería social para generar urgencia

Dominio no legítimo al pasar el cursor sobre el enlace

El propósito del ataque era robar credenciales o redirigir al usuario a un sitio falso.

Actions Taken

(How)

El correo fue analizado sin interactuar con los enlaces

Se confirmó la naturaleza maliciosa del mensaje

El correo fue marcado como phishing

Se bloqueó el dominio y el remitente

Se notificó al usuario afectado

El incidente fue documentado y cerrado

Impact Assessment

No se evidenció interacción del usuario con el enlace malicioso.
No hubo compromiso de cuentas ni sistemas.

Final Verdict

El incidente fue contenido exitosamente en fase temprana.
No se requirió escalamiento a SOC L2 ni activación del equipo DFIR.

Recommendations

Capacitación continua a usuarios sobre phishing

Mantener actualizadas las reglas de detección

Monitoreo constante del tráfico de correo

Analyst Notes

Este incidente fue manejado completamente por un Analista SOC L1, siguiendo los procedimientos estándar de detección, análisis y respuesta inicial.
