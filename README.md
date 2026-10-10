# EchoDrop: Blind Accessible Battle Royale

This repo contains a browser-based prototype for a blind-accessible battle royale game concept.

## What it includes
- Fully accessible screen-reader feedback using live regions and speech synthesis
- Audio cues for danger, loot, hit events, and match status
- Simple lobby creation and join flow
- Real-time-inspired battle loop with zone shrink, bots, loot, and win/lose states
- Keyboard controls designed for easy gameplay without visual precision
- A command feed with AI-like narration and tactical audio prompts

## How to run
1. Open `index.html` in a browser.
2. Use the lobby panel to create or join a room.
3. Press Start Match.
4. Play with keyboard controls:
   - WASD / Arrow Keys: move
   - Space: fire
   - E: loot nearby item
   - M: scan nearest threat
   - Q: AI callout
   - V: toggle voice chat simulation

## Recommended browser use
- Chrome or Edge is best for speech synthesis and modern browser APIs.
- Use a screen reader like NVDA or VoiceOver for the best accessibility experience.

## Accessibility notes
This is a prototype, not a full production game backend. It focuses on the core interaction loop and audio-first gameplay design for visually impaired players.

## Future upgrades
- WebRTC real voice chat between players
- multiplayer lobby backend with Node.js and Socket.IO
- richer game maps and equipment systems
- true spatial audio with panning and 3D sound
- AI-generated tactical narration and combat callouts
