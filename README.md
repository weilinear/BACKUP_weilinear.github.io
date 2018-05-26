# Homepage for Wei Li

This site is based on the **[Minimal Mistakes](http://mmistakes.github.io/minimal-mistakes)** theme, a two-column responsive Jekyll theme perfect for powering your GitHub hosted blog.

## License

Feel free to adapt this theme to your site without linking back to me or including a disclaimer, although letting me know would be nice.
The whole site is based on Dr. Jordi Pont-Tuset's and Prof. Dr. Laura Leal-Taixe's site!

The publication is generated with JabRef together with the [publist.layout](https://truongnghiem.wordpress.com/2010/09/29/introducing-publist/) 
which generates html.

## To run it locally
```
jekyll serve --watch --port 5000
```

## Some tips if you would like to fork and tweak it
* The publist.layout controls the layout of the generated html file from bib. It's pretty straight forward to change although the code looks complicated.
  * You'll need to add pllinks field in JabRef
  * It has an image on the left from `images/papers/{bibtexkey}.png`
  * The publist.layout works with JabRef version < 4.0
* It uses email obfuscator
  * It uses [email protect plugin](https://github.com/vwochnik/jekyll-email-protect) for site wide reference to site.owner
  * It uses [email obfuscator](https://github.com/psmiraglia/jekyll-email-obfuscator) for other references to the email address.
