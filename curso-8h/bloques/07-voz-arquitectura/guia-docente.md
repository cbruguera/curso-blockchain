# Guía del docente — Bloque 7: Diseño de la solución: arquitectura de referencia

**Parte II — Proyecto: la voz como compromiso** · 55 min

## Pregunta guía

> ¿Qué se guarda, qué se firma y qué se publica — y dónde vive cada cosa?

## Objetivos

1. Recorrer la arquitectura completa, de la captura a la verificación.
2. Justificar qué información va dentro y cuál fuera de la cadena.
3. Describir el expediente de prueba que permite verificar años después.
4. Identificar las decisiones de diseño que siguen abiertas.

## Guion y tiempos

| Tiempo | Segmento | Nota |
|---|---|---|
| 5' | Apertura: la arquitectura en una lámina | — |
| 12' | Captura y consentimiento | Qué ocurre antes de grabar: informar, identificar, registrar el contexto. |
| 12' | Procesamiento y firmas | Hash del audio, metadatos, firma del declarante y firma del sistema. Qué firma cada uno y por qué. |
| 10' | Anclaje | Qué se publica, en qué red y con qué frecuencia. Lotes y árboles de Merkle para abaratar. |
| 10' | Custodia del audio | Cifrado, control de acceso, retención y supresión sin romper la prueba. |
| 6' | Verificación por un tercero | El recorrido completo visto por quien tiene que darla por buena. |

## Preparación previa

<!-- TODO: qué leer, probar o tener abierto antes de entrar al aula -->

## Dudas frecuentes

<!-- TODO: 3-5 preguntas que siempre salen, con respuesta breve y honesta -->

## Errores frecuentes al explicar esto

<!-- TODO: simplificaciones que se vuelven falsas -->

## Si vas corto de tiempo

<!-- TODO: qué segmento se recorta primero y qué no se puede tocar -->

## Referencias

- C2PA — *Coalition for Content Provenance and Authenticity*, especificación técnica.
- W3C — *Verifiable Credentials Data Model*.
- OpenTimestamps — anclaje por lotes con árboles de Merkle.
- <!-- TODO: referencias del proyecto propio, ver /proyecto-voz -->
