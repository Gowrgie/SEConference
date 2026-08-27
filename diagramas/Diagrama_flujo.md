---
config:
  theme: redux
---
flowchart TB
    A([Inicio])--> B[/Capturar datos del asistente/]
    B-->C{¿Datos completos?}
    C-->s1[Si]-->D[Registrar asistente]
    D-->E[/Mostrar Confirmación/]
    C-->s2[No]-->F[/Mostrar información faltante/]
    E-->G([Fin])
    F-->E

