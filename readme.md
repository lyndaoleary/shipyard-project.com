# Shipyard Project
## Requirements
- [Hugo](http://hugo.spf13.com/)
- Your favorite text editor

## Developers' Guide 
The recommended method to view and test Shipyard documentation changes is to run Hugo with the LiveReload option for instant feedback.
```
$ cd site
$ hugo server -w
```

Then view the Shipyard documentation here: [http://localhost:1313/](http://localhost:1313/)

## Deployment
Production deployments can be done by either:
- Serving via `hugo server`
- Running `hugo` to build and then copying the `public` directory up to your production web server (e.g. Apache, nginx or IIS)