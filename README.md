# Sketch.Nono.Ma - Dark    

A custom theme for WriteFreely blog pages.  
Original theme: https://write.as/themes/sketch-nono-ma

![image](https://user-images.githubusercontent.com/15841958/221346178-c50c6764-9cbf-440e-a6f2-25a65c62412e.png)

## Install

Copy the content of [write.css](write.css) and [footnotes.js](footnotes.js) into the **Custom CSS** field on the **Customize** page.  

You need to provide the font-files in [userfonts](userfonts) on the machine hosting your blog.
If you use `nginx` as a reverse proxy, as suggested in the [documentation](https://writefreely.org/start), you have to change the default configuration:

Change `location ~ ^/(css|img|js|fonts)/` to  
`location ~ ^/(css|img|js|fonts|userfonts)/` and copy the `userfonts` directory to your `static` directory.  
**e.g.:**
~~~bash
cp -r userfonts /var/www/example.com/static
~~~

That's it!

## Conclusion

Feel free to contribute in any way.
