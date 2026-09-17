# Guía del docente — Sesión 2: Cómo se prueba algo digitalmente

**Parte I — Fundamentos** · 55 min

## Pregunta guía

> ¿Cómo demuestro que este archivo es mío, que existía el martes y que no lo he tocado desde entonces?

## Objetivos

1. Explicar qué demuestra una firma digital y por qué una clave no es una persona.
2. Describir el anclaje por hash: se publica la huella, el original se queda contigo.
3. Reconstruir una verificación años después y saber qué hay que conservar para ello.
4. Comparar el anclaje en cadena con el sello de tiempo de un tercero de confianza.

## Guion y tiempos

| Tiempo | Segmento | Nota |
|---|---|---|
| 5' | Apertura: tres preguntas sobre un archivo | Quién, qué y cuándo. Ejemplos del aula: una versión de software, un dataset, una maqueta, un acta. |
| 12' | Probar quién: firmas | Par de claves, qué demuestra la firma y dónde se rompe la cadena hacia la persona. |
| 12' | Probar qué y cuándo: huella y anclaje | Se publica la huella; el contenido nunca sale de tu poder. Regla de oro del curso. |
| 8' | Verificar dentro de cinco años | Qué hay que conservar para que la prueba siga en pie. Anclaje por lotes. |
| 10' | La alternativa clásica | Sello de tiempo de un tercero de confianza: cómo funciona y cuándo es mejor opción. |
| 5' | Tres errores caros | Anclar el archivo entero, anclar datos personales, perder el original. |
| 3' | Cierre | Una lámina de valor legal, sin entrar: se retoma en la Parte II. |

## Preparación previa

<!-- TODO: qué leer, probar o tener abierto antes de entrar al aula -->

## Dudas frecuentes

<!-- TODO: 3-5 preguntas que siempre salen, con respuesta breve y honesta -->

## Errores frecuentes al explicar esto

<!-- TODO: simplificaciones que se vuelven falsas -->

## Si vas corto de tiempo

<!-- TODO: qué segmento se recorta primero y qué no se puede tocar -->

## Referencias

- Merkle, R. (1979). *A Certified Digital Signature*.
- OpenTimestamps — especificación y herramienta de aula.
- RFC 3161 — Time-Stamp Protocol.
- Antonopoulos, A. *Mastering Bitcoin*, cap. 4 (referencia técnica).
- Mención local: Ley 25.506 de Firma Digital (AR). <!-- TODO: verificar vigencia con fuente local -->
