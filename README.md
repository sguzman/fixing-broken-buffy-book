# fixing-broken-buffy-book
Repo to fix a broken epub of a really old book. It kept breaking epub tools

Run with

`pandoc --verbose --metadata-file meta.yaml --from textile --to epub3 --output buffy.epub -- buffy.txt`
