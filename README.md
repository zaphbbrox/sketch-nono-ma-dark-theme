# Sketch.Nono.Ma  

A custom theme for WriteFreely blog pages.  
Original theme: https://write.as/themes/sketch-nono-ma

**IMAGE_PLACEHOLDER**

## Install

Copy the content of [write.css](write.css) and [footnotes.js](footnotes.js) into the **Custom CSS** field on the **Customize** page.  

You need to provide the font-files in [userfonts](userfonts) on the machine hosting your blog.
If you use `nginx` as a reverse proxy, as suggested in the [documentation](https://writefreely.org/start), you have to change the default configuration:

Change `location ~ ^/(css|img|js|fonts)/` to  
`location ~ ^/(css|img|js|fonts|userfonts)/` and copy the `userfont` directory to your `static` directory.  
**e.g.:**
~~~bash
cp -r userfonts /var/www/example.com/static
~~~

That's it!

## Conclusion

Feel free to contribute in any way.