# Prueba técnica — Forward Deployed Engineer (011h)

## La situación

En 011h, el equipo de compras recibe **actas de adjudicación de obra** de constructoras y proveedores. Cada uno las manda como quiere —un PDF, un CSV, un export de su ERP— y con su propia forma de nombrar las cosas.

Por otro lado tenemos el **banco de partidas**: nuestro catálogo de unidades de obra, con código, descripción, unidad y precio de referencia. Es la fuente contra la que, en teoría, deberíamos poder contrastar lo que nos facturan.

Un responsable de compras nos lo resume así:

> *"Me llegan contratos de todas partes y en cualquier formato. Yo lo que necesito es saber si lo que estoy a punto de firmar está en línea con lo que pagamos normalmente, y qué líneas debería mirar con lupa antes de dar el OK. Ahora mismo eso lo hace una persona a mano, contrato a contrato, y no da abasto."*

Eso es lo que tienes delante. A partir de aquí, es tuyo.

## Los datos

En esta carpeta tienes:

- `banco_de_partidas.xlsx` — el catálogo de referencia. Es un export real, con el ruido de un dato real.
- `contratos/` — 7 adjudicaciones de 7 obras, tal cual llegaron. No hemos limpiado ni ordenado nada.

## Lo que esperamos de ti

Que hagas algo útil con esto para esa persona de compras. **Qué es "útil", con qué profundidad, y hasta dónde llegas, lo decides tú** y nos lo explicas.

**No buscamos que resuelvas todo el problema, sino ver qué decides resolver primero y por qué.** Una buena forma de encuadrarlo: si al acabar tus 2–3 horas la persona de compras dedicara cinco minutos a usar lo que has construido, ¿qué decisión podría tomar mejor que hoy? Empieza por ahí.

No es una prueba de ingeniería clásica: no medimos volumen de código ni pulcritud, sino cómo conviertes un problema ambiguo en algo que **funcione y le sirva a alguien**. Eso sí, tiene que funcionar de verdad con estos datos —no basta con un plan sobre cómo lo harías.

Si te faltan datos o contexto y tienes que asumir algo, asúmelo y explícalo. Preferimos ver decisiones razonadas a que te quedes esperando la información perfecta.

Ten presente que quien recibe tu resultado es la persona de compras del principio —no es técnica—, así que lo que entregues tiene que servirle **a ella**.

## Cómo lo miramos (somos transparentes)

- **Criterio para acotar:** qué decides atacar, qué dejas fuera a conciencia y cómo tratas lo ambiguo.
- **Olfato con los datos:** qué ves en estos datos que nadie te ha señalado.
- **Comunicación:** si tu resultado le sirve de verdad a alguien no técnico.

## Reglas del juego

- Pensada para **2–3 horas**. Preferimos ver dónde pones el límite a que nos entregues 12 horas de trabajo. Lo que dejes fuera, cuéntalo como "qué haría con más tiempo".
- Stack y formato, a tu elección. Usa las herramientas con las que trabajas a diario, **IA incluida** —nos interesa cómo la diriges, no que no la uses.
- En la **entrevista** será donde nos enseñes el resultado y cómo razonas tus decisiones.
- No se requiere conocimiento previo de construcción. Si un término no te suena, enséñanos cómo resuelves la ambigüedad —eso es parte de lo que medimos.