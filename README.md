# homebrew-tap

Homebrew formulae for [t-shahan](https://github.com/t-shahan)'s projects.

```bash
brew install t-shahan/tap/virga
```

`brew` expands `t-shahan/tap` to this repository, so the `homebrew-` prefix
never appears in the install command.

## Formulae

| Formula | Project |
|---|---|
| `virga` | [Terminal weather app with an hourly precipitation chart](https://github.com/t-shahan/virga) |

## These files are generated

Do not edit `Formula/*.rb` by hand. Each project's release workflow rewrites its
formula on every release, with the version and the checksums read back off the
published release, and pushes the result here. A hand edit is lost at the next
release.

For `virga` that workflow is
[`.github/workflows/release.yml`](https://github.com/t-shahan/virga/blob/main/.github/workflows/release.yml).
