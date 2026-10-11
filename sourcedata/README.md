# sourcedata

Original release files of the source dataset, as far as they can be redistributed.

## Release files stored under their release names (added 2026-10-11)

1282 release files of Pennsieve dataset 467 version 1 (https://discover.pennsieve.io/datasets/467/version/1) are listed under `sourcedata/pennsieve-467-v1/` with their release paths.
They take no extra storage: each is a git-annex pointer to the same content as the BIDS file named in
`sourcedata/SOURCEDATA_POINTERS.tsv`.

- 0 are `identical`: byte for byte the released file.
- 1282 are `scrubbed`: the privacy-scrubbed copy used in the BIDS part, not the released bytes. Scrubbed files had datetime values, HDF5 object times, text datasets or PNG tIME/tEXt chunks rewritten; `sourcedata/pennsieve-467-v1/scrub_log.tsv` lists every change with the SHA-256 of both versions.

The unscrubbed originals are not redistributed here; they remain available from the public source.
