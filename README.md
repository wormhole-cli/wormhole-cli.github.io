# wormhole-cli.github.io

The site for [wormhole](https://github.com/wormhole-cli/wormhole), served at https://wormhole-cli.github.io.

The pages live in [`site/`](https://github.com/wormhole-cli/wormhole/tree/main/site) of the main repo. This repo only
holds the workflow that publishes them, every six hours and on demand:

```bash
gh workflow run pages.yml -R wormhole-cli/wormhole-cli.github.io
```
