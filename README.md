# DON’T MOVE — Audio Prototype 0.1

An audio-only interactive fiction prototype.

A hidden voice can hear your footsteps through your headphones. To help it, you have to move. To protect it, you have to stay quiet.

## Play

Open `index.html` in a browser, preferably with headphones.

- **Hold SPACE**, **hold WALK**, or enable real-step detection to walk.
- **Stop walking** when the voice asks.
- **Tap choices** to respond.
- **Whisper “I’m here”** to reassure the voice—but speaking during a search is risky.

## Prototype goal

Test whether a player instinctively slows down, stops, or hesitates to speak when a fictional hidden voice is in danger.

## Core mechanic

Your real movement becomes the hidden character’s risk:

- Walking creates footsteps.
- The hidden voice hears them.
- During a search, footsteps and speech increase suspicion.
- Staying still protects the voice but pauses the story.

## Next steps

- Replace browser speech synthesis with recorded performances.
- Add a second, spatialized voice in the hiding place.
- Add an overheard conversation between the hidden voice and another character.
- Add a capture sequence that changes the voice’s audio treatment.
- Add captions, transcript mode, mono fallback, and adjustable narration/effects/ambience volumes.
