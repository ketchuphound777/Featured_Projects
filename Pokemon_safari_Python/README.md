Pokémon Safari Zone (Python)
A text‑based adventure game built in Python that simulates a Safari Zone experience using real Pokémon data from the PokéAPI. The player explores the safari, encounters Pokémon of different rarity levels, and attempts to catch as many as possible before running out of safari balls.

Project Overview
This project uses the PokéAPI to fetch the first 151 Pokémon and categorize them into rarity groups:

common

uncommon

rare

legendary

The game then generates random encounters based on weighted probabilities and allows the player to interact with each Pokémon using safari‑style mechanics.

Features
Live API integration using the PokéAPI

Random encounter system with weighted rarity

Catch mechanics based on Pokémon type

Safari ball inventory system

Special events:

1/8192 chance for a shiny

1/65586 chance for Pokérus

Player interaction system:

Throw safari ball

Throw rock

Throw bait

How It Works
Fetches Pokémon data from the PokéAPI

Categorizes Pokémon by rarity using probability rolls

Generates encounters using weighted randomness

Calculates catch and flee chances dynamically

Tracks player inventory and caught Pokémon

Ends the safari when the player runs out of safari balls

Skills Demonstrated
API requests (requests library)

JSON parsing

randomized game logic

control flow and loops

state tracking

error handling

Notes
This project was created as part of my Python learning journey and demonstrates my ability to work with APIs, randomness, game logic, and user interaction in a terminal‑based environment.
