# skelepico-theme

Live Demo: http://skelepico.com/

Skelepico Theme is a bare-bones theme for Pico CMS created on the Skeleton framework. It uses exclusively elements from Skeleton except for these features that I've added:

## Skelepico Theme 1.0.0
+Added a sticky responsive navigation bar (coded exclusively in HTML/CSS)*
+Added footer styles (to make credits look nicer)*
+Added Skeleton's normalize.css code to the begining of the skeleton.css file and minified the code. This gives an extra point for Google PageSpeed score.
+No validation errors here: https://validator.w3.org/nu/

*An asterisk indicates a design feature that can be removed by clearing the code from the custom.css file.*

## Theme Notes

The base.twig template is full width but you can still add your own columns using HTML in the .md files (this page uses the base template). index.twig and page.twig are also full width and ready for your customizations.

**This theme comes with demo content in the .twig templates. You will need to make adjustments accordingly!**

### Notes from Jon Beckett's (https://github.com/jonbeckett) code:

+If you want to make a blog, create a folder within /content, and put your posts in it (purely to keep them organised - they are actually picked up by the blog page by having dates). For each post, use the template "post", and make sure they have a date metadata property. Then make a content file in the root of /content with the template "blog", and it will list all pages it finds that have a date in their metadata, in reverse order.
+The blog template has Disqus built-in. If you want to use it, add $config["disqus"]="username"; to the config file, and use the "post" template for blog posts.
+The base theme has Google Analytics built-in. If you want to use it, add $config["google-analytics"]="property_id"; to the config file.

## Additional Documention

Skeleton 2.0.4 documentation is available here (http://getskeleton.com/) or view the archived version (https://web.archive.org/web/20170424210340/http://getskeleton.com/).

Pico 1.0.4 documentation is available here (http://picocms.org/docs/) or view the archived version (https://web.archive.org/web/20170424210548/http://picocms.org/docs/).

Twig 1.26.0 documentation is available here (https://twig.sensiolabs.org/doc/1.x/) or view the archived version (https://web.archive.org/web/20170424210858/https://twig.sensiolabs.org/doc/1.x/).
