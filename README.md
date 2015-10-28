# NodeSchool SF

Welcome to the NodeSchool San Francisco chapter's repository. We use this
repository for our website and almost all our communication.

You can see the website here: http://nodeschool.io/sanfrancisco/


## Talk to us

We utilize [GitHub Issues](https://github.com/nodeschool/sanfrancisco/issues)
like a message board and keep almost all of our communication in the open. If
for any reason you need to contact an organizer privately you may contact us
directly.


## Team

| Name | GitHub | Twitter |
|---|---|---|
| Daniel Paz-Soldan | [danpaz](https://github.com/danpaz)  | [@danpazsoldan](https://twitter.com/danpazsoldan) |
| Josh Finnie | [joshfinnie](https://github.com/joshfinnie) | [@joshfinnie](https://twitter.com/joshfinnie) |
| Juan Caicedo | [JuanCaicedo](https://github.com/JuanCaicedo)  | [@_juancaicedo](https://twitter.com/_juancaicedo) |
| Robbie Holmes  | [robbiethegeek](https://github.com/robbiethegeek) | [@robbiethegeek](https://twitter.com/RobbieTheGeek)|


## Contributing to the website

The website is just basic HTML, CSS and JavaScript. It runs on [GitHub
Pages](https://pages.github.com/).

### Running locally

When you're editing the website it's convenient to run the website locally to
see your changes.

Make sure you install dependencies via:

```bash
$ npm install
```

Then you can run the website via:

```bash
$ npm start

# > nodeschooldc@1.0.0 start /projects/washingtondc
# > http-server .

# Starting up http-server, serving . on: http://0.0.0.0:8080
# Hit CTRL-C to stop the server
```

Now you can visit `http://localhost:8080/` in your browser to see the website.

By default it will start the server on port `8080`. If you want to specify a
different port use:

```bash
$ PORT=3000 npm start
```

Where `3000` is any port you choose.
