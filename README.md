# temper-manifest

The app catalog the apps page in [temper](https://github.com/shitpostindustries/temper) fetches at runtime.
`apps.json` is checked against `schema.json` before temper uses it, and temper falls back to its last good
copy, then the one it shipped with, if this can't be read. The source of truth is `catalog/` in the temper
repo, this is a published copy of it.
