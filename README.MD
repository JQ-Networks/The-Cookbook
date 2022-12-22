# README

## Website [cookbook.jq.mk](https://cookbook.jq.mk)

## Quick Start

### Setup hexo

You should have NodeJS and npm installed on your computer.

macOS:

```
brew install npm
```

Linux: [See This](https://stackoverflow.com/questions/39981828/installing-nodejs-and-npm-on-linux)

Windows: [See This](https://www.youtube.com/watch?v=dQw4w9WgXcQ)

Install Hexo

```
npm install -g hexo
```

### Create a new recipe

``` bash
$ hexo new "My New Recipe"
```

More info: [Writing](https://hexo.io/docs/writing.html)

Edit the MD file in the output.

There is a template [Post模板.md](Post模板.md) under root directory.

### Publish

```
git add .
git commit -m "Recipe: My new Recipe"
git push
```

## Test on local machine

### Run server

``` bash
$ hexo server
```

More info: [Server](https://hexo.io/docs/server.html)

### Generate static files

``` bash
$ hexo generate
```

More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to remote sites

``` bash
$ hexo deploy
```

More info: [Deployment](https://hexo.io/docs/one-command-deployment.html)
