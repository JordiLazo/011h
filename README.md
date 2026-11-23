## La situación

En la empresa, el equipo de compras recibe actas de adjudicación de obra de constructoras y proveedores. Cada uno las envía en su propio formato (un PDF, un CSV, un export de su ERP) y con su propia forma de nombrar las cosas.

Por otro lado existe el banco de partidas: el catálogo interno de unidades de obra, con código, descripción, unidad y precio de referencia. Es la fuente contra la que, en principio, debería poder contrastarse lo que se factura.

Un responsable de compras lo resume así:

> *"Me llegan contratos de todas partes y en cualquier formato. Yo lo que necesito es saber si lo que estoy a punto de firmar está en línea con lo que pagamos normalmente, y qué líneas debería mirar con lupa antes de dar el OK. Ahora mismo eso lo hace una persona a mano, contrato a contrato, y no da abasto."*

## Los datos disponibles
 
- `banco_de_partidas.xlsx`: el catálogo de referencia. Es un export real, con el ruido propio de un dato real.
- `contratos/`: 7 adjudicaciones de 7 obras distintas, tal como llegaron, sin limpiar ni ordenar.
## El objetivo
 
Construir una herramienta que le resulte útil a la persona de compras en su día a día. La pregunta que guía el proyecto es: **si esta persona dedicara cinco minutos a usar la herramienta, ¿qué decisión podría tomar mejor que hoy?**
 
En concreto, la herramienta debería ayudarle a:
 
- Saber si un contrato está en línea con los precios habituales de la empresa.
- Identificar qué líneas conviene revisar en detalle antes de aprobarlo.
- Reducir el trabajo manual de revisar contrato por contrato.
## Consideraciones
 
- **Usuario no técnico:** el resultado debe ser claro y utilizable por alguien de compras, sin conocimientos de programación.
- **Datos heterogéneos:** los contratos llegan en formatos y nomenclaturas distintas, y el catálogo contiene ruido. Parte del trabajo es entender y tratar esas inconsistencias.
- **Funcionamiento real:** la solución tiene que funcionar con estos datos concretos, no quedarse en un planteamiento teórico.
- **Alcance acotado:** se prioriza resolver primero lo que más valor aporta y dejar documentado qué queda fuera y qué se haría en una siguiente fase.
- **Supuestos explícitos:** donde falte información o contexto, se asumen hipótesis razonadas y se documentan.
