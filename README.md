# Rocq-community website

Entries are currently added manually to `index.md`.
The file `index.html` is generated using
[pandoc](https://pandoc.org) as follows:
```shell
pandoc -f markdown+emoji -s -o index.html index.md
```
