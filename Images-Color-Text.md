# Images in HTML

**_\<img src="./path" alt="">_**

This is the basic definition to add an image to your ste. the src used to add the path of your image and the alt to add a descreption to the search engines and as a messge shown to the user if the image can't be loaded.

It is very important to choose an image with dimentions that fit in its container in the site. Also to make it load fast you need to make your image with jpeg, gif, and png.

# Colors

In general every color is a mix of red, blue, and green.

When picking foreground and background colors, it is important to ensure that there is enough contrast for the text to be legible

selector {

color: value;

}

So colors in general have many ways define a value:

- by name (red,blue,etc)
- by hex number (#88888, #888)
- by rbg(0-255,0-255,0-255)
- by rbga(0-255,0-255,0-255,0-1)

In rbga the a parameter used to define the opacity

# Text & Fonts

fonts types uses:

- Serif: used with the printed texts and it eazy to read
- Sans-Serif: used with small fonts and low resolution screens
- Monospace: this kind of fonts have the same width for every line with will make it well aligned and eazier to follow and read.

Not all devices have the same set of fonts so you need to add genaric font at the end like this (**_font-family: Georgia, Times, serif;_**). Also you can add the font into your project files and use the font from your file not from the local device that user have.

@font-face {

font-family: 'ChunkFiveRegular';

src: url('fonts/chunkfive.eot');

}

h1, h2 {

font-family: ChunkFiveRegular, Georgia, serif;

}
This example explane how to add a font family from your dirictory and not rely on the user fonts set.

- @font-face: used to start a block that used to define new font
- font-family:when it within @font-face it will define the name to be used in your css.

text-indent can be used to define the logo. So you can git the text-indent value like -999px thx add a background-image. By this techniech you will help the search engines to get your pad at the same time you will geta nice logo from the background image.
