# Across the Ages

Across the Ages is a responsive, accessible two-team social board game for teens and older adults. It includes a shared opening path, a player-selected Safe or Risk branch, hearts, two-dice movement capped at five spaces, interactive card decks, Talk It Out secret prompts, Act It Out, Acting Jeopardy with a two-minute timer, Wild Card, Swap Place, and a restartable win state.

## Run locally

Open `index.html` in a modern browser. No build step or dependencies are required.

The room-code flow is designed around a central `state` object and uses `BroadcastChannel` when multiple tabs on the same device are open. A production remote game can replace the small `broadcast()` adapter with a WebSocket, Firebase, or Supabase transport without changing the board/game rules.
