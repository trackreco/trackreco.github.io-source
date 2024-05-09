# trackreco.github.io-source
pelican source for website 

![](https://travis-ci.org/trackreco/trackreco.github.io-source.svg?branch=master)

Created Trackreco GitHub Organization
Using [Pelican](http://getpelican.com/) to generate website with fork of [pelican-themes](https://github.com/trackreco/pelican-themes) theme

Using Travis to build website -- [how-to](http://zonca.github.io/2013/09/automatically-build-pelican-and-publish-to-github-pages.html)

Recipe for local deploy, using `uv` and `gh`:

```bash
gh repo clone trackreco/trackreco.github.io
gh repo clone trackreco/trackreco.github.io-source
cd trackreco.github.io-source
uv venv --python python3.8
uv pip install --exclude-newer 2020-01-01 -r requirements.txt
git clone https://github.com/trackreco/pelican-themes.git
git clone --recurse-submodules https://github.com/getpelican/pelican-plugins
unzip tipuesearch.zip
cp -r Tipue\ Search\ 7.1/tipuesearch pelican-themes/static/
cp pelican-plugins/tipue_search/pelican/plugins/tipue_search/* pelican-plugins/tipue_search/.
. .venv/bin/activate.fish
make html
cp -R output/* ../trackreco.github.io/.
```
