# $name$

$cabal_description$

## Building the project

The project must be "configured" at least once everytime `$name;format="camel"$.cabal` changes, this can be done with:

    cabal configure

If you wish to run the unit tests you will have to run:

    cabal configure --enable-tests

Then finally build it with:

    cabal build

See `cabal build --help` for more build options.

## Yesod Development

To run the development server run

    \$ yesod devel

From the same directory as the `$name;format="camel"$.cabal` file

See [**here**] [yesod-home] for more information on **Yesod**.

## Running Unit Tests

**After** running `cabal build`, you can run the unit tests with the command:

    cabal test

## Adding Unit tests

Unit tests are written with [**doctest**] [doctest-github], for instructions on how to add unit tests 
see the **doctest** [**User Guide**] [doctest-userguide].

[doctest-github]: https://github.com/sol/doctest-haskell "sol/doctest-haskell on GitHub.com"
[doctest-userguide]: https://github.com/sol/doctest-haskell/blob/master/README.markdown#usage "doctest Usage Guide"
[yesod-home]: http://www.yesodweb.com/ "Yesod Web Application Framework"
