## Development
After cloning the project, we load the themes via
git submodules, and launch the development server:

```shell
git submodule init
git submodule update
hugo server
```

## Deployment
The website is hosted on github pages. To deploy
changes, we generate the static content, commit
everything (especially the docs/ directory) and
push:


```shell
hugo
git add --all
git commit
git push
```
