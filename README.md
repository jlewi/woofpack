# Woofpack

A directory of dogs in the Crestmoore Park neighborhood in San Bruno CA.

```sh {"id":"01J4D1ZX7SJR5C4YDGR9Y3A4QT"}
hugo mod init
```

```sh {"id":"01J4D2J8SAFZNAHP7ZTQKFPS4B"}
~/Downloads/hugo mod get
```

```sh {"id":"01J4D1YNRV0TNARN0B1VRZ65P5"}
~/Downloads/hugo serve
```

```sh {"id":"01J4D2M9R2Y7CZBQNKP5XP6J0R"}
./pull-images.sh
```

## Adding New Dogs

Create a directory with the dogs name
And put the pictures of the dog in the directory

```sh {"id":"01J4FTRVSXZDW2QM07HBZRYBG8"}
mkdir -p content/maggie
```

* Create an index yaml file

```sh {"id":"01J4FV4N3A4MN0B1JXJHNFKZ0T"}
cp content/ollie/index.md content/maggie/index.md
cp content/ollie/index.md content/jessica/index.md
```

# References

[Hugo Gallery Theme](https://github.com/nicokaiser/hugo-theme-gallery/tree/main)
