# APP

GitHub Pages tools hub.

- [英文單字卡](./vocabulary/)

## Deployment
GitHub Settings → Pages → Deploy from branch: `main` / root.

## Vocabulary storage
The vocabulary page can read/write a `data/vocabulary.json` file through GitHub Contents API. For private storage, create a **separate private data repository** and set its owner/name and JSON path in the page's configuration. The webpage requires a fine-grained GitHub token entered at runtime (Contents: read/write on the selected data repository), and never embeds or persistently stores a token. Do not expose private vocabulary data in a public Pages repository.
