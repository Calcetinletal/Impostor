# Impostor (tema sí, palabra no)

Juego social para familia/amigos. Todos conocen la **palabra secreta** excepto el **impostor**, que solo conoce el **tema/categoría** (p. ej. *Famosos, Películas, Lugares…*). Se juega dando pistas y votando quién parece ir a ciegas.

## Cómo funciona

- **Jugadores normales:** ven **Tema + Palabra**
- **Impostor:** ve **solo el Tema** (no ve la palabra)

Por turnos, cada jugador da una **pista corta** relacionada con la palabra **sin decirla literalmente**. Tras 1–2 vueltas, se debate y se vota quién es el impostor.

> Opcional: si pillan al impostor, se le puede dar una última oportunidad de **adivinar la palabra**.

## Reglas rápidas (recomendadas)

1. El anfitrión genera una ronda (nº de jugadores y tema).
2. Cada jugador abre su enlace privado y mira su rol.
3. **Ronda de pistas:** 1 palabra o 1 frase corta por jugador.
4. **Debate** (30–90s).
5. **Votación** (a mano alzada o señalando).
6. Si queréis, **revelación** + (opcional) “último intento” del impostor.

## Cómo jugar (cada uno en su móvil)

1. Abre el juego desde GitHub Pages (ver abajo).
2. Pulsa **Generar ronda**.
3. Copia y envía por WhatsApp/Telegram el enlace de cada **Jugador 1..N** a la persona correcta.
4. Cada jugador abre su enlace y pulsa **Revelar** cuando quiera (idealmente a solas).
5. Empezad la ronda de pistas por voz (en persona o por llamada).

## Deploy en GitHub Pages

1. Sube `index.html` a la raíz del repo.
2. En GitHub: **Settings → Pages**
3. **Source:** Deploy from a branch  
   **Branch:** `main`  
   **Folder:** `/ (root)`
4. Guarda y abre la URL que te da GitHub Pages, por ejemplo:  
   `https://TUUSUARIO.github.io/NOMBRE-REPO/`

## Personalización

Las categorías/palabras están en el objeto `DATA` dentro de `index.html`.

Ejemplo:

```js
const DATA = {
  "Famosos": ["..."],
  "Películas": ["..."],
  "Lugares": ["..."]
};
