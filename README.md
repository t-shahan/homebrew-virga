# homebrew-virga

The Homebrew tap for [Virga](https://github.com/t-shahan/virga), a terminal
weather app with an hourly precipitation chart.

```bash
brew install t-shahan/virga/virga
```

`brew` expands `t-shahan/virga` to this repository, so the `homebrew-` prefix
never appears in the install command. This repository used to be named
`homebrew-tap`; anyone who tapped `t-shahan/tap` keeps getting updates through
GitHub's rename redirect and does not need to retap.

## These files are generated

Do not edit `Formula/*.rb` by hand. Virga's release workflow rewrites the
formula on every release, with the version and the checksums read back off the
published release, and pushes the result here. A hand edit is lost at the next
release.

That workflow is
[`.github/workflows/release.yml`](https://github.com/t-shahan/virga/blob/main/.github/workflows/release.yml).
