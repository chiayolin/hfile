hfile
=====

`hfile` is a shell script that enables you the ability to show or hide hidden files in Finder on OS X. 
But really, the script itself is just the aliases of `defaults write com.apple.finder AppleShowAllFiles
YES` and `defaults write com.apple.finder AppleShowAllFiles NO`. So if you want to save some key strokes, 
then you might find this shell script useful.

Installing
----------

If you have Homebrew installed on your machine then:

```sh
brew tap chiayolin/cask
brew install hfile
```

Else, clone the repository, `cd` into the repository, then paste that at a terminal prompt:

```sh
ln -s $(pwd)/hfile /usr/local/bin/hfile
```


Usage
-----

**Show** hidden files: 

```sh
$ hfile show
```

**Hide** hidden files:

```sh
$ hfile hide
```

You can also use `1` and `0` instead of `show` and `hide`:

```sh
$ hfile 1 # this will **show** the hidden files
```

Use the argument `help` to print help messages.


License
-------

The code is licensed under the [GPL 3.0][gpl3] License. 
[gpl3]: https://raw.githubusercontent.com/chiayolin/hfile/master/LICENSE 
