# Custom Hitsounds!

A fork of 111116's webosu. Added a section in settings for custom hitsounds.   
 * Hitsounds must be in the .ogg format and multiple can be dragged in at once.   
`Here is a list of the required hitsounds:   
[
'normal-hitnormal.ogg',
'normal-hitwhistle.ogg',
'normal-hitfinish.ogg',
'normal-hitclap.ogg',
'normal-slidertick.ogg',
'soft-hitnormal.ogg',
'soft-hitwhistle.ogg',
'soft-hitfinish.ogg',
'soft-hitclap.ogg',
'soft-slidertick.ogg',
'drum-hitnormal.ogg',
'drum-hitwhistle.ogg',
'drum-hitfinish.ogg',
'drum-hitclap.ogg',
'drum-slidertick.ogg',
'combobreak.ogg',
]`
Without these, webosu will automatically default to normal hitsounds. Any corrupt hitsounds will be replaced with default ones. 
   
## Original README:    
A browser rhythm game where players click circles following rhythm of the music.

Powered by [PixiJS](https://www.pixijs.com). Beatmap source: [Sayobot](https://osu.sayobot.cn).

Note: This is an unofficial implementation of [osu!](https://osu.ppy.sh). Scoring and judgement rules differ from official versions. Some music might not be perfectly syncing. Modes other than osu! (std) are unsupported.

## Screenshots

web page:

![webpage](screenshots/page3.jpg)

game in action:

![webpage](screenshots/clip3.gif)

## Hosting

Set up a web server with root directory located where `index.html` is in.

To host a separate live score, redirect send/fetch api requests to localhost:3000/3001 respectively, and change the api url in `index.html` and `scripts/overlay/score.js` accordingly. Then run:

```bash
nohup node api.js &
```

## Todos (probably)

- beatmap hitsounds
- pp & user system

## License Notes

Some media files are copyrighted by [ppy](https://github.com/ppy/) and other people. Check their respective license before you use them.
