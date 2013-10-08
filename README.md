# Giter8 Haskell Template

An empty **Haskell** project using **cabal** and the [**Yesod Web App Framework**] [yesod-home], and **PostgreSQL** for the persistent layer.

# Giter8

This template uses [**Giter8**] [giter8] to fill out default values in the cabal project file.

## Installing Giter8

Detailed instructions for installing **Giter8** can be found [**here**] [giter8-install].

But for **UNIX**y systems the following will suffice:

    curl https://raw.github.com/n8han/conscript/master/setup.sh | sh
    ~/bin/cs n8han/giter8
    ~/bin/g8

This will install `cs` and `g8` in `~/bin`, it would be worthwhile adding `~/bin` to your `PATH`.

## Using Giter8

This template can be downloaded with the command (assuming `~/bin` is added to your path):

    g8 domdere/yesod-postgres

[giter8]: https://github.com/n8han/giter8 "n8han/giter8 on github.com"
[giter8-install]: https://github.com/n8han/giter8/blob/master/README.markdown#installation "Installation instructions for Giter8"
[yesod-home]: http://www.yesodweb.com/ "Yesod Web Application Framework"
