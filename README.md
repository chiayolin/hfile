hfile
=====

`hfile` is a shell script that enables you the ability to show or hide hidden files in Finder on OS X. 
But really, the script itself is just the aliases of `defaults write com.apple.finder AppleShowAllFiles
YES` and `defaults write com.apple.finder AppleShowAllFiles NO`. So if you want to save some key strokes, 
then you might find this shell script useful.

Installing
----------

Place the script into somewhere in the `$PATH` on you machine.

Usage
-----

*Show* hidden files: 

```sh
$ hfile show
```

*Hide* hidden files:

```sh
$ hfile hide
```

You can also use `1` and `0` instead of `show` and `hide`:

```sh
$ hfile 1 # this will *show* the hidden files
```

Need some help? No worries!

```sh
$ hfile help
```


License
-------

The code is licensed under the [GPL 3.0][gpl3] License. 
[gpl]: https://raw.githubusercontent.com/chiayolin/hfile/master/LICENSE 
