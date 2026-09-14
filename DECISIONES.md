# Bitácora de decisiones

Por qué el curso es como es. Se actualiza cada vez que se cambia el plan.
El plan en sí vive en [`curso-8h/PROGRAMA.md`](curso-8h/PROGRAMA.md).

## 2026-09-14 — Diseño inicial

**Duración: 8 h, en 8 bloques de 55 min.**
Requisito duro. Se eligió el bloque de 55 min en lugar de la sesión de 2 h para que el curso se
pueda impartir en 4 sesiones de 2 h, 8 de 1 h o 2 jornadas de 4 h sin rehacer el material.

**Público: cualquiera, sin asumir perfil.**
El curso interesa a emprendedores y a juristas, pero también podría asistir un ingeniero. Se descartó
escribir material separado por perfil o secciones de «doble lectura»: un solo texto, una sola lectura.
El ángulo jurídico-probatorio decide qué entra y en qué orden, no el tono ni el vocabulario.

**La definición de blockchain ocupa una lámina.**
Se asume que el asistente ya tiene una noción básica. El bloque 1 no explica qué es: explica sus tres
garantías (integridad, orden temporal, autoría) y sus cuatro «no garantías», que es donde se cometen
los errores caros.

**Estructura 5 + 3, con el proyecto de la voz como Parte II.**
Se valoró dedicarle un solo bloque (insuficiente) y hacerlo hilo conductor de todo el curso (ata
demasiado el material a un caso). Se optó por tres bloques: problema, arquitectura y taller de ataque.
Los bloques 2 y 3 están deliberadamente montados como *probar quién* / *probar qué y cuándo*, que es la
descomposición que la Parte II necesita: preparan el proyecto sin anunciarlo.

**Qué se recortó y dónde fue a parar.**
Minería, consenso formal, DeFi, capas 2, rollups, MEV, interoperabilidad y DAOs salen del núcleo y
quedan esbozados en [`material-extendido/`](material-extendido/) como lectura opcional y cantera de
monográficos. Tokens, dinero y stablecoins es el único tema con peso propio que quedó fuera: si se
recupera, sale de los bloques 3 o 5.

**El bloque 8 no defiende la cadena.**
El taller final compara el sistema diseñado con la alternativa simple —un sello de tiempo cualificado
de un prestador— y admite «aquí no hace falta blockchain» como conclusión válida. Es el punto del curso
donde se demuestra criterio.

**Marp para las slides.**
Markdown versionable con diffs legibles, exportable a PDF y HTML. Descartados Reveal.js (más control
visual, mucho más costoso de mantener) y publicar cada bloque como artefacto.

## Pendiente de decidir

- **Jurisdicción.** Todo el material normativo asume marco europeo (RGPD, eIDAS, MiCA). Si el destino
  es LatAm, hay que rehacer las referencias de los bloques 2, 3 y 5 (no el esqueleto).
- **Tokens y dinero:** ¿vuelve al núcleo o se queda en material extendido?
- **Formato real de impartición**, que condiciona dónde conviene cortar y cuántas pausas prever.
- El contenido de los bloques está sin desarrollar: el esqueleto está cerrado, los `<!-- TODO -->` no.
