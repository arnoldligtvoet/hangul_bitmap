When I needed a Hangual (Korean) bitmap font for a project I searched high and low and found this hidden gem.

Cloned it into it's own repo, so it can be found easier. All credits go to biud436 (https://github.com/biud436/MV/tree/master/Hangul).

I used this font succesfully in a project using Jimp on NodeJS:

Jimp.loadFont('./img/hangul/hangul.xml').then(function (font) {
  // add text here onto image
}
