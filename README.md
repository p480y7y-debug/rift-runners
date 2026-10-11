# Rift Runners

A free browser arena prototype with a trophy road, smarter practice bots, and experimental peer-to-peer rooms.

## Match filling
- Practice matches contain 1 human player and 4 bot opponents.
- Online rooms start when a friend connects and fill the remaining slots with 3 bot players, for 5 fighters total.
- In online rooms, the host simulates bot movement and shares bot state with the joining player. Peer-to-peer networking is still experimental and can behave differently across networks.

## Progression
- Win a bot match: +10 trophies.
- Lose a bot match: −7 trophies, minimum 0.
- Trophy cap: 80,000.
- Trophies, wins, losses, and personal best are stored locally in the current browser/device.

## Controls
- Mobile: left virtual stick to move; BLAST to shoot; DASH to evade.
- Desktop: WASD or arrow keys to move, Space to shoot, Shift to dash.

This is an early prototype, not a full competitive game. Online match results and cross-device progression are not yet a secure ranked system.
