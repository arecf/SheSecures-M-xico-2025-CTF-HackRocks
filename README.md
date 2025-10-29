# SheSecures-M-xico-2025-CTF-HackRocks
Este repositorio documenta mi participación en los laboratorios del **CTF SheSecures México 2025**, organizado por **HackRocks**.   A lo largo del evento trabajé en retos de distintas áreas de la ciberseguridad: reconocimiento web, explotación de APIs, ingeniería inversa y criptografía. 
## Resumen ejecutivo

Participé activamente en 5 laboratorios con objetivos y técnicas diferentes. Completé con éxito cuatro de ellos y dejé un quinto parcialmente resuelto, donde construí una cadena de análisis y descifrado (RSA + triple-AES) pero no llegué a obtener la bandera final por falta de tiempo.  
Durante el CTF apliqué metodologías de reconocimiento, explotación controlada, análisis de código y trabajo con criptografía aplicada.

---

## Laboratorios

- **LAB 01 — La Trama Mitchell** — Criptografía básica y análisis de estructura de cifrado.  
- **LAB 02 — Matilda en la Nube** — Exploración de almacenamiento y descubrimiento de datos expuestos.  
- **LAB 03 — Los Ecos de Maryam** — Ingeniería inversa de bytecode para reconstruir mensajes ocultos.  
- **LAB 04 — La Red de Agnodice** — Análisis de APIs, extracción de credenciales y manejo de tokens.  
- **LAB 05 — El Espejo de Artemisia** — Criptografía híbrida y pipeline de descifrado (parcialmente resuelto).

---

## Herramientas y prácticas clave

Usé una combinación de herramientas estándar y buenas prácticas:

- Entorno: **Kali Linux** y entornos virtuales de Python (venv).  
- Interacción con servicios: **curl**, manejo de cookies y headers HTTP.  
- Procesamiento y análisis: **jq**, scripts en **Python 3** (PyCryptodome para pruebas de cifrado).  
- Desarrollo seguro: entornos aislados para instalaciones (venv), verificación de salidas y almacenamiento controlado de artefactos de prueba.  
- Documentación: registro paso a paso de comandos, salidas y conclusiones.

---

## Logros destacados

- Identifiqué y enumeré endpoints internos y tablas accesibles en APIs protegidas.  
- Obtuve credenciales válidas y gestioné tokens para sesiones administrativas.  
- Revertí lógica de un fragmento de bytecode para reconstruir un mensaje oculto.  
- Descifré parcialmente un flujo híbrido (RSA → AES×3) y monté el pipeline de descifrado.

---

## Agradecimientos

Gracias a **HackRocks** y al programa **SheSecures México 2025** por la organización.  
Agradezco especialmente al equipo del **Secretariat of the Inter-American Committee against Terrorism (CICTE)** y a todos los facilitadores que hicieron posible este CTF.

---
