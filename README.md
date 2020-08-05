# Elixir Koans (Part 1)

[![Build Status](https://travis-ci.org/elixirkoans/elixir-koans.svg?branch=master)](https://travis-ci.org/elixirkoans/elixir-koans)

Elixir koans is a fun way to get started with the elixir programming language. It is a tour
of the most important features and idiomatic usage of the language.

Note that this repository is a clone of the official one, with only a part of the koans.
We will complete the rest of the koans as we avance in our course. If you want to run the full
set of Koans, please got to the official project Web page at http://elixirkoans.io/

### Prerequisites

You need to have Elixir installed. Please refer to the [official guide](http://elixir-lang.org/install.html) for instructions.

First, clone the repo from BitBucket:

```sh
git clone https://bitbucket.org/lgban/elixir-koans-part1
cd elixir-koans-part1/
```

Create a git repository for your own work (e.g. in Bitbucket). Disconnect your local copy of the repository from the original one:

```sh
git remote remove origin
```

and reconnect it with your newly created repository. Use the following command:

```sh
git remote add origin <URL to your git Repository>
```

PLEASE COMMIT YOUR CODE AS OFTEN AS POSSIBLE. YOU CAN DO IT WHEN YOU COMPLETE EACH ONE OF THE KOAN GROUPS (there are 4 groups in Part 1).


> NOTE: If you have a Windows box, you might require to use `mix.bat` instead of `mix`.

Next, fetch mix dependencies by running:

```sh
$ mix deps.get
```

You might get prompted to install further dependencies. Reply "y".

On Linux, you'll need to install `inotify-tools` to be able
to use the autorunner in this project.

### Running

With the dependencies installed, navigate to the root directory of this project and run:

```sh
$ mix meditate
```

You should see the first failure. Open the corresponding file in your favourite text editor
and fill in the blanks to make the koans pass one by one.
The autorunner will give you feedback each time you save.

Good luck!