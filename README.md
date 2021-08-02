# Stork Demo

Download Stork.

```sh
$ cd ~/softwares
$ wget https://files.stork-search.net/releases/v1.2.1/stork-macos-10-15
$ cd -
```

Build the index.

```sh
$ ~/softwares/stork-macos-10-15 build --input config.toml --output federalist.st
```

Query the index.

```sh
$ ~/softwares/stork-macos-10-15 search --index federalist.st --query "liberty"
```

Visit index.html and query on the web. Note it points to an index on the public web.