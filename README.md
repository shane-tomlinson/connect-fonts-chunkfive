# connect-fonts-chunkfive

A [connect-fonts](https://github.com/shane-tomlinson/connect-fonts) fontpack for the ChunkFive font.

## Usage

1. Include [connect-fonts](https://github.com/shane-tomlinson/connect-fonts) in a node module.
```
const font_middleware = require("connect-fonts");
```

2. Include the font packs that you want to serve.
```
const chunkfive = require("connect-fonts-chunkfive");
```

3. Add a middleware by calling the `setup` function.
```
    app.use(font_middleware.setup({
      fonts: [ chunkfive ],
      allow_origin: "https://exampledomain.com"
    }));
```

4. Add a link tag to include the font CSS.
```
    <link href="/en/chunkfive/fonts.css" type="text/css" rel="stylesheet"/ >
```

5. Set your CSS up to use the new font by using the "Chunk Five" font-family.
```
    body {
      font-family: 'Chunk Five', 'sans-serif', 'serif';
    }
```


## Author
* Shane Tomlinson
* shane@shanetomlinson.com
* stomlinson@mozilla.com
* set117@yahoo.com
* https://shanetomlinson.com
* http://github.com/stomlinson
* http://github.com/shane-tomlinson
* @shane_tomlinson

## Credits

Original font set downloaded from fontsquirrel.com. Chunk Five created by [The League of Moveable Type](http://www.theleagueofmoveabletype.com/)

## License

This software is dual licenced under version 2.0 of the MPL and version 1.1 of the SIL Open Font License

  https://www.mozilla.org/MPL/

  http://scripts.sil.org/OFL

