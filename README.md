# 2022-sourmash-sketchfrom

This repository contains examples, demonstrations, and support scripts
for building custom sourmash databases, using
[the new `sourmash sketch fromfile` command](https://github.com/sourmash-bio/sourmash/pull/1885)
and related additions to sourmash.

See [sourmash#1671](https://github.com/sourmash-bio/sourmash/issues/1671) for
the overall discussion.

## Examples

See [an example of building a private database](./example.private/).

Another example: [building protein and DNA databases starting from genomes](./example.private+protein).

## Scripts and code

* `fasta-to-fromfile.py` - build a `fromfile` CSV file from a list of FASTA files.
* `genbank-to-fromfile.py` - build a `fromfile` CSV file from a list of FASTA files downloaded from Genbank
* `kiln.py` - support library for building `fromfile` CSVs.
* `mass-rename.py` - a script to bulk-rename sourmash signatures.
* `sigs-to-manifest.py` - a script to extract and/or update sourmash manifests from many databases.
