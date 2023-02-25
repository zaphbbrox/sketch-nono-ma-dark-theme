# Sketch.Nono.Ma - Dark    

[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg?style=for-the-badge)](http://creativecommons.org/publicdomain/zero/1.0/)
![Code: CSS](https://img.shields.io/badge/code-css-green?style=for-the-badge&logo=css3)

Based on the original theme [**Sketch.Nono.Ma**](https://write.as/themes/sketch-nono-ma).  
Thanks for this wonderful theme! 

## Changes

  - replaced the fonts
  - changed background-colors
  - changed color of headlines, links, etc. from `red` to `hotpink`
  - raised `max-width` for `#post article.norm` to 70%
  - set `text-decoration` of `body#post article h2#title` to `underline`


## Screenshot 

![image](https://user-images.githubusercontent.com/15841958/221346178-c50c6764-9cbf-440e-a6f2-25a65c62412e.png)

## Used fonts

For the headers I use the [Oswald font from Google Fonts](https://fonts.google.com/share?selection.family=Oswald:wght@300).  
For all other elements I use the [Iosevka font](https://github.com/be5invis/Iosevka).

## Install

Clone the repo:  

    git clone https://github.com/zaphbbrox/sketch-nono-ma-dark-theme.git

Copy the content of [write.css](write.css) ~~and [footnotes.js](footnotes.js)~~[^1] into the **Custom CSS** field on the **Customize** page.  

You need to provide the font-files in [sketch-nono-ma-dark-theme/fonts](fonts) on the machine hosting your blog.  
Just copy the `fonts` directory to your `static` directory.  

**e.g.:**
~~~bash
cp sketch-nono-ma-dark-theme/fonts/* /var/www/example.com/static/fonts/
~~~

That's it!

## Conclusion

Feel free to contribute in any way.

---

[^1]: _(adding custom JS is currently not supported on WriteFreely)_

