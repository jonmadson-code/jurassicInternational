{\rtf1\ansi\ansicpg1252\cocoartf2865
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # Jurassic Jaws \'97 Claude Code Project Brief\
\
## What this is\
A browser-based HTML5 Canvas game for the Jurassic International games site.\
Built with plain HTML, CSS, and JavaScript \'97 no frameworks, no dependencies.\
Must run as a single self-contained HTML file.\
\
## Game concept\
2D side-scrolling survival game. Player is a dinosaur surviving waves of hunters.\
\
## Player\
- Moves up/down/left/right with arrow keys or WASD\
- Has 3 lives\
- Green rectangle sprite\
\
## Enemies (Hunters)\
- Spawn from the right, chase the player\
- Red rectangle sprites\
- >200px away: shoot projectiles at player\
- <50px away: swing axe (instant damage)\
- 5% chance any hunter spawns as "Raccoon Rick":\
  - Gold rectangle sprite\
  - 10\'d7 movement speed\
  - 10\'d7 damage (instant kill on contact)\
\
## Items (spawn randomly, 10% chance each)\
- Dog Treats (Tan): Hold SPACE to fire a minigun of treats from player's mouth\
- Shield (Blue): Temporary 1-hit invulnerability vs bullets and axes\
\
## UI\
- Lives counter (top left)\
- Treat ammo bar (top left)\
- Score based on distance survived (top right)\
\
## Tech rules\
- Single HTML file output\
- Placeholder colored rectangles for all sprites (no image assets)\
- Canvas-based rendering\
- Must work on desktop browsers (Chrome, Firefox, Safari)\
\
## Where it lives\
This game will be embedded/linked from the Jurassic International games hub page.\
Keep the file named: jurassic-jaws.html\
```\
\
**Step 3 \'97 Open Claude Code in that folder and run this first prompt:**\
```\
Read CLAUDE.md and build jurassic-jaws.html \'97 the complete playable game \
described in the brief. Use HTML5 Canvas. Single file, no dependencies.}