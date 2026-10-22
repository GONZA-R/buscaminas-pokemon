# Buscaminas Pokémon

Un tablero lleno de Pokémon y una pregunta, por ejemplo **«¿Es de tipo Agua?»**.
Tocá todos los Pokémon que dicen **SÍ**… porque los que dicen **NO** son minas: ¡explotan!

## Cómo se juega

- Arriba aparece una pregunta: tipo, color, forma, evolución, tamaño… o **¿Quién hace este sonido?** 🔊 (suena el grito de un Pokémon).
- Los tipos no se ven en las cartas: ¡tenés que saberlos!
- Tenés 3 Poké Balls (vidas). Cada Pokémon que explota te saca una.
- Cuando encuentran todos los que cumplen, viene otra pregunta. Cada 3 preguntas cambia el tablero.
- **Fácil:** 16 Pokémon, tipo, color y sonido, sin reloj.
- **Medio:** 24 Pokémon, también forma, evolución y generación, 45 s por pregunta.
- **Difícil:** 30 Pokémon, también altura y peso, 30 s por pregunta.
- Podés elegir de qué generaciones salen los Pokémon (de la 1 a la 9).

## Modos

- **Solo:** jugás vos. Los récords quedan guardados en el dispositivo.
- **2 en este equipo:** en el mismo celu o compu.
- **2 online:** cada uno en su celu. Uno crea la partida y le pasa el código de 4 letras (o el link) al otro.

## Reglas

- **Poké Balls:** 3 vidas; si errás, perdés una. De a 2 se juega por turnos: si acertás, seguís tocando;
  si explota, le toca al otro (cada toque tiene tiempo límite). Gana quien tenga más puntos después de 8 preguntas,
  o el que no se quede sin Poké Balls.
- **Contrarreloj (1, 2, 3 o 5 minutos):** no hay vidas; si errás, explota y pasás a la pregunta siguiente.
  Gana quien haga más puntos antes de que se termine el tiempo. Online, cada uno va a su ritmo con sus propias
  preguntas y ve los puntos del otro en vivo. En el mismo equipo, juega uno y después el otro.
- El modo online usa la misma base de Firebase que «¿Quién es ese Pokémon?» (partidas en `games/bm-CÓDIGO`).

También está el **buscaminas clásico** con Voltorb escondidos en el pasto (`clasico.html`).

## Archivos

| Archivo | Qué es |
|---|---|
| `index.html` | El juego de preguntas: diseño, lógica y datos de los 1025 Pokémon |
| `clasico.html` | El buscaminas clásico (Fácil 9×9, Medio 16×16, Difícil 16×30) |
| `g/g1.json` … `g/g9.json` | Las imágenes de cada generación; se bajan solo las que hacen falta |

Sprites de [PokeAPI](https://github.com/PokeAPI/sprites). Pokémon es marca de Nintendo / Game Freak. Juego hecho por diversión, sin fines de lucro.
