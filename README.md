# docker-pandoc-xelatex
Docker container for Pandoc with Latex tools and xelatex in order to use --template

```
docker run -v `pwd`:/source jpbernius/pandoc-xelatex
```

You can also use all the [pandoc](http://pandoc.org/) options 

```
Input formats:  commonmark, docbook, docx, epub, haddock, html, json*, latex,
                markdown, markdown_github, markdown_mmd, markdown_phpextra,
                markdown_strict, mediawiki, native, opml, org, rst, t2t,
                textile, twiki
                [ *only Pandoc's JSON version of native AST]
Output formats: asciidoc, beamer, commonmark, context, docbook, docx, dokuwiki,
                dzslides, epub, epub3, fb2, haddock, html, html5, icml, json*,
                latex, man, markdown, markdown_github, markdown_mmd,
                markdown_phpextra, markdown_strict, mediawiki, native, odt,
                opendocument, opml, org, pdf**, plain, revealjs, rst, rtf, s5,
                slideous, slidy, texinfo, textile
                [**for pdf output, use latex or beamer and -o FILENAME.pdf]
  ```
