# TransportationOrderServer0

## Justificación de que el workflow funciona correctamente

A continuación se muestra la evidencia de que el workflow de **GitHub Actions** del microservicio *TransportationOrderServer0* se ejecuta correctamente.  
Las capturas demuestran que:

- El workflow se activa automáticamente tras cada `push`
- El paso **build (compile)** finaliza correctamente
- El paso **verify (tests)** también finaliza sin errores
- Toda la ejecución aparece en verde, indicando éxito total

### Evidencia 1 — Ejecución general del pipeline
![Captura 1](results/Captura%20de%20pantalla%202025-12-05%20a%20las%2017.41.23.png)

### Evidencia 2 — Detalle de los pasos build y verify completados con éxito
![Captura 2](results/Captura%20de%20pantalla%202025-12-05%20a%20las%2017.41.37.png)
