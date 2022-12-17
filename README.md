# Lyric Music

Search Lyrics

## Installation

```
npm i lyric-music
```

### Example

```js
const lyrics = require("lyric-music"); 

async function liriks(title){
	try {
		const lyric = await lyrics(title);
		console.log(lyric);
	} catch (error) {
		console.log("Unknow lyric.");
	}
}
liriks("tabun")
```

## Contributions

Software contributions are welcome. If you are not a dev, testing and reproting bugs can also be very helpful!

## Questions?

Please open an issue if you have questions, wish to request a feature, etc.