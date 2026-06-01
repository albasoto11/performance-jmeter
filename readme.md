## Instrucciones de ejecución - Prueba de carga login

**Requisitos**:
- JMeter 5.6.3
- Java JDK 11+
- Git

**Pasos**:
1. Clonar repositorio: git clone <https://github.com/albasoto11/performance-jmeter.git>
2. cd performance_jmeter


**Observaciones**:
- Los datos de usuarios están en datos/data.csv
- El TPS objetivo es 20, ajustar threads según resultados preliminares
- Las aserciones validan respuesta < 1.5s y éxito del login