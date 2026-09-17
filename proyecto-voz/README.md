# Proyecto: la voz como herramienta de compromiso jurídico

Documento vivo. Sostiene las sesiones 5-7 del [curso de 8 h](../curso-8h/) y va más allá de él:
es una línea de trabajo propia que merece sesiones monográficas.

## El problema

Una persona se compromete a algo hablando. Meses después, alguien lo niega. ¿Qué se puede demostrar?

Son cuatro problemas distintos que se confunden constantemente:

| Pregunta | Qué hay que probar | Herramienta principal |
|---|---|---|
| ¿Quién habló? | Autoría | Biometría de voz + firma de una identidad acreditada |
| ¿Qué dijo? | Integridad del audio | Hash del archivo |
| ¿Cuándo? | Momento cierto | Sello de tiempo / anclaje |
| ¿Con qué intención? | Consentimiento informado | Diseño del flujo de captura |

La cadena resuelve bien las dos del medio. Las otras dos son el trabajo difícil, y es donde
la mayoría de propuestas del mercado hacen trampa.

## Hipótesis de trabajo

<!-- TODO: formular la hipótesis central del proyecto -->

## Preguntas abiertas

- ¿Qué aporta el anclaje en cadena frente a un sello de tiempo cualificado de un PSC, más allá de la
  independencia del proveedor? ¿Justifica esa diferencia la complejidad añadida?
- La voz es dato biométrico (RGPD art. 9). ¿Qué base jurídica sostiene el tratamiento y cómo se
  concilia la retención con el derecho de supresión?
- Con clonación de voz accesible a cualquiera, ¿la biometría de voz sigue aportando algo, o solo
  desplaza el problema a la identidad del dispositivo y del momento de captura?
- ¿Qué exige un tribunal para dar por buena una prueba así? ¿Cambia según jurisdicción?
- ¿Quién custodia el audio y qué pasa cuando esa entidad desaparece?

## Estado del arte por revisar

- C2PA (procedencia de contenido) y su aplicabilidad al audio.
- ASVspoof / NIST SRE: tasas de error reales en detección de suplantación.
- Credenciales verificables (W3C) para vincular declarante e identidad acreditada.
- Soluciones existentes de notarización de audio y qué prometen de más.

## Jurisdicción

**Argentina.** Las referencias normativas locales (Ley 25.506 de firma digital, Ley 25.326 de
protección de datos, registro de PSAV) están marcadas con `TODO` porque provienen de conocimiento con
fecha de corte: **hay que verificarlas con fuente local antes de dictar**. El marco europeo
(eIDAS, RGPD, MiCA) se menciona como referencia comparada, no como contenido.
