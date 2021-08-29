# discord-soundscapes

## idea

- you can add a bunch of music/sound effects to play/pause at will
- you can set up "scenes" thatll auto switch what music/effects are available on screen
- youd log in with discord so any "scenes" and stuff would be saved automatically
- sends sound through music bot in discord

## technical

- node web server (http, ill let nginx and cloudflare take care of https)
  - i can add built in https later if i want
- typescript
  - maybe react for the front end?
- discord.js
- object oriented primarily so keep the files organized as such

- hardest part may be combining audios for the stream
  - ill do this first and then base the rest of it around this function
    - i.e. switching scenes will run both so that transitions may occur, meaning the audio combination must work with already combined audio
