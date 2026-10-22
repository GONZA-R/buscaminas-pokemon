# Buscaminas Pokémon

Un tablero lleno de Pokémon y una pregunta, por ejemplo **«¿Es de tipo Agua?»**.
Tocá todos los Pokémon que dicen **SÍ**… porque los que dicen **NO** son minas: ¡explotan!

## Cómo se juega

- Tenés 3 Poké Balls (vidas). Cada Pokémon que explota te saca una.
- Cuando encontrás todos los que cumplen, viene otra pregunta. Cada 3 preguntas cambia el tablero.
- Sumás puntos por cada acierto y extra por terminar rápido y sin errores.
- **Fácil:** 16 Pokémon, preguntas de tipo y color, sin reloj.
- **Medio:** 24 Pokémon, también forma, evolución y generación, 45 s por pregunta.
- **Difícil:** 30 Pokémon, también altura y peso, tipos ocultos, 30 s por pregunta.
- Podés elegir de qué generaciones salen los Pokémon (de la 1 a la 9).
- Los récords quedan guardados en el navegador de cada dispositivo.

También está el **buscaminas clásico** con Voltorb escondidos en el pasto (`clasico.html`).

## Archivos

| Archivo | Qué es |
|---|---|
| `index.html` | El juego de preguntas: diseño, lógica y datos de los 1025 Pokémon |
| `clasico.html` | El buscaminas clásico (Fácil 9×9, Medio 16×16, Difícil 16×30) |
| `g/g1.json` … `g/g9.json` | Las imágenes de cada generación; se bajan solo las que hacen falta |

Sprites de [PokeAPI](https://github.com/PokeAPI/sprites). Pokémon es marca de Nintendo / Game Freak. Juego hecho por diversión, sin fines de lucro.
