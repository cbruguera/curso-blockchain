# Guía del docente — Clase 02: Criptografía sin matemáticas

**Módulo 1 — Fundamentos** · Duración total: 120 min

## Pregunta guía

> ¿Cómo se demuestra que un documento no ha cambiado y que lo firmó quien dice?

## Objetivos

1. Describir qué es una función hash y qué propiedades la hacen útil.
2. Distinguir clave pública de clave privada y entender qué es firmar digitalmente.
3. Explicar para qué sirve un árbol de Merkle con una analogía.

## Guion y tiempos

| Tiempo | Bloque | Nota |
|---|---|---|
| 15 min | Apertura: la huella digital de un archivo | Demo en vivo: cambiar una coma y ver cómo cambia el hash entero. |
| 25 min | Funciones hash y sus propiedades | Determinista, rápida, irreversible, resistente a colisiones. SHA-256 en la práctica. |
| 25 min | Claves pública y privada | Analogía del buzón: cualquiera echa cartas, solo uno la abre. Por qué no es una contraseña. |
| 25 min | Firmas digitales | Firmar no es cifrar. Qué prueba una firma: autoría, integridad, no repudio. |
| 20 min | Árboles de Merkle | Verificar que algo está en una lista enorme sin descargarla entera. |
| 10 min | Cierre | Estas tres piezas son el 90 % de la criptografía que usa una blockchain. |

## Preparación previa

<!-- TODO: qué debe leer, probar o tener abierto el docente antes de entrar al aula -->

## Dudas frecuentes y cómo responderlas

<!-- TODO: 3-5 preguntas que siempre salen, con una respuesta breve y honesta -->

## Errores frecuentes al explicar este tema

<!-- TODO: simplificaciones que se vuelven falsas y hay que evitar -->

## Referencias

- Merkle, R. (1979). *A Certified Digital Signature*.
- NIST FIPS 180-4, *Secure Hash Standard*.
- Antonopoulos, A. *Mastering Bitcoin*, cap. 4 (Keys and Addresses).
