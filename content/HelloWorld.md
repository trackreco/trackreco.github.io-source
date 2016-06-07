Title: Hello World
date: 2015-05-10 14:53
Slug: Hello World
Category: Blog
Tags:  news
Authors: Kyle Cranmer
Status: draft

Initial post for DIANA-HEP.

Status of build:

![](https://travis-ci.org/s2i2-hep/s2i2-hep.github.io-source.svg?branch=master)

To do: 

   * setup DNS for `www.s2i2-hep.org` subdomain using [this guide](https://help.github.com/articles/tips-for-configuring-a-cname-record-with-your-dns-provider)
   * setup DNS for `s2i2-hep.org` apex domain using [this guide](https://help.github.com/articles/tips-for-configuring-an-a-record-with-your-dns-provider/)
      * ok, working with .net currently, need to decide.

Progress:

  * Created [S2I2-HEP GitHub Organization](https://github.com/s2i2-hep)
  * Using [Pelican](http://getpelican.com) to generate website
  * Using Travis to build website -- [how-to](http://zonca.github.io/2013/09/automatically-build-pelican-and-publish-to-github-pages.html)
  * deploying to GitHub pages [http://s2i2-hep.github.io](http://s2i2-hep.github.io)
  * created `CNAME` file to use custom url `s2i2-hep.org`
  * Check math: $pp \to \tilde{\chi}_1^0 \tilde{\chi}_1^\pm$
  * Check code 

```python
    def main():
        print 'welcome to Pelican'
```

   * Check embed ipython notebook
   {% notebook BasicRooFitExample.ipynb cells[2:10] %}




