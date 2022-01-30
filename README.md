# lighthouse-server-ci

Created from [this guide](https://github.com/GoogleChrome/lighthouse-ci/blob/main/docs/recipes/heroku-server/README.md)
After installation run:

```
heroku login contacto@boolean.cl
heroku run --app boolean-lighthouse-server-ci "npm install -g @lhci/cli && lhci wizard"
```

Also see [this article](https://raybogman.com/jekyll-travis-lighthouse-heroku-ci-cd#8-run-lhci-wizard)