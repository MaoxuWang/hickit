## Manual

Modified from https://github.com/lh3/hickit, add cell barcode information(extracted by readname) to .pairs file and dedup contacts by cellbarcode and position rather than position alone

```sh
hickit –i ${id}.contacts.seg.gz -o - | gzip > ${id}.contacts.pairs.gz
```

<img src="doc/function_explain.png" width=70%>

## Files changed
- hickit.h
- io.c
- pair.c

Changes are marked.
