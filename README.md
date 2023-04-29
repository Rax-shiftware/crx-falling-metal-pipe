# Falling Metal Pipe Chrome Extension

This is a silly little project that makes the falling metal pipe meme sound
play every time you open a new tab in your browser.

- [Chrome](https://chrome.google.com/webstore/detail/falling-metal-pipe/nbgmlhcjfjkbpflgcfemflmcdgegcckj)
- [Firefox](https://addons.mozilla.org/firefox/addon/falling-metal-pipe/)
- [Edge](https://microsoftedge.microsoft.com/addons/detail/gbpinnmffiiippbfedpihdmnlcbaljja)

The core of it is using manifest version 3 and an offscreen document to play
the sound effect, it's neat enough I guess.

Now also with a Firefox edition that uses the extended background scripts
capabilities firefox still supports for manifest version 3, rather than
supporting web workers.
