## alexhaydock.co.uk

Live repo for my site, hosted at https://alexhaydock.co.uk

Theme based on [hermit-V2](https://github.com/1bl4z3r/hermit-V2), which is included as a Git Submodule.

If this is the first time cloning the repo to your machine, don't forget to run:
```sh
git submodule update --init --recursive
```

Once cloned, you can test the site with:
```
hugo serve
```

And build (into `/public/`) with:
```
hugo
```

In production, this site is deployed to GitHub Pages by a GitHub Action that comes straight from the Hugo documentation.
