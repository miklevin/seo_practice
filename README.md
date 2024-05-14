# seo_practice

> Mostly Jupyter Notebooks where I practice SEO Tricks

I like Jupyter Notebooks. In particular, I like them in JupyterLab, because it
lets you do browser automation and manage your files with the ease of local
files. The cloud is nice and most advice will lead you to Google Colab for
Notebooks and VSCode for Python. But I find JupyterLab-Desktp, the standalone
destop installable app from GitHub, strikes the best balance for SEO purposes.

A few things that I always need to remember go at the top of this file. When you
make a new local git repo and you need to "connect" it to a new repo you made at
GitHub, the magic words are...

```cli
git remote add origin git@github.com/miklevin/seo_practice.git
git push -u origin main
nbstripout --install
```

This is because I had earlier `pip install nbstripout` on my Python environment
so that whenever I add a `.ipynb` file to to a repo, it automatically strips out
the extra metadata that makes Notebook git repos ugly.

