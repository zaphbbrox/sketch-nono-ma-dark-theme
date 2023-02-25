# Sketch.Nono.Ma - Dark    

[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

A fork of the Sketch.Nono.Ma theme for WriteFreely blog pages.    
Original theme: https://write.as/themes/sketch-nono-ma  
Thanks for this wonderful theme! 

Mainly I changed it to dark mode and use custom fonts.

## Screenshot 

![image](https://user-images.githubusercontent.com/15841958/221346178-c50c6764-9cbf-440e-a6f2-25a65c62412e.png)

## Used fonts

For the headers I use the [Oswald font from Google Fonts](https://fonts.google.com/share?selection.family=Oswald:wght@300).  
For all other elements I use the [Iosevka font](https://github.com/be5invis/Iosevka).

## Install

Copy the content of [write.css](write.css) ~~and [footnotes.js](footnotes.js)~~[^1] into the **Custom CSS** field on the **Customize** page.  

You need to provide the font-files in [userfonts](userfonts) on the machine hosting your blog.
If you use `nginx` as a reverse proxy, as suggested in the [documentation](https://writefreely.org/start), you have to change the default configuration:

Change 
~~~bash
location ~ ^/(css|img|js|fonts)/
~~~ 
to
~~~bash  
location ~ ^/(css|img|js|fonts|userfonts)/
~~~ 
and copy the `userfonts` directory to your `static` directory.  
**e.g.:**
~~~bash
cp -r userfonts /var/www/example.com/static
~~~

That's it!

## Conclusion

Feel free to contribute in any way.

---

[^1]: _(adding custom JS is currently not supported on WriteFreely)_

