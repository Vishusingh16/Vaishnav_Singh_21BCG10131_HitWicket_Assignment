# NAME - Vaishnav Singh
# Reg No - 21BCG10131

# Updated Chess Project

This project has been updated according to the new requirements outlined by Hitwicket.
## Game Overview
- **Board Size:** 5x5 grid
- **Characters:** Pawn, Hero1, Hero2, with unique movement rules
- **Game Flow:** Turn-based gameplay with real-time websocket communication

## Setup Instructions
1. Clone the repository or download the project zip file.
2. Install the required dependencies using `npm install` for the server.
3. Run the server using `npx nodemon`
4. Launch the client by opening http://localhost:3000/
5. Connect and start the game!

## Websocket Communication
- **Client-Server Communication:** Websocket connection established using `Socket.io` library.
- **Real-time Chats:** Chats in Real Time.
- **Game initialization**
- **Player move**
- **Game state update**
- **Invalid move notification**
- **Game over notification**

## Move Validation
- Prevent invalid moves according to the game rules.
- Ensure moves are within the 5x5 grid boundaries.

## Edge Cases
- Handle simultaneous move attempts.
- Manage disconnections and reconnections during the game.
- Handle out-of-turn moves gracefully.
