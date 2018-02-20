Horizontal DevOps
-----------------

Horizontal DevOps presentation; Rob Bayliss and Geoff St. Pierre. Scaling your teams productivity horizontally.

Run Slideshow Locally
---------------------

The reveal.js slideshow includes a `.lando.yml` file to run the node stack. If you don't have lando you can get it here: [Lando](https://devwithlando.io).

```bash
# Clone the repo
git clone git@github.com:thinktandem/HorizontalDevOps.git

# Start the app
cd HorizontalDevOps
lando start
```

The first build of the app will run `npm install` and drop you into a watch mode that is watching `index.html` and `reveal.scss` files for changes. On subsequent starts to get into the watch mode:

```bash
cd reveal.js
lando npm start
```
