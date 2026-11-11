# DVARA JBang catalog

Run DVARA tools with [JBang](https://www.jbang.dev/download/). JBang downloads Java 25 the first time if you don't have it.

| Command | What it does |
|---|---|
| `jbang litellm-to-dvara@dvarahq config.yaml -o dvara-import/` | Converts a LiteLLM proxy `config.yaml` into a DVARA `gateway.yaml`, with a report of what maps, what changes and what has no equivalent. Source: [dvara-litellm-importer](https://github.com/dvarahq/dvara-litellm-importer) |
| `jbang bifrost-to-dvara@dvarahq config.json -o dvara-import/` | Converts a Bifrost `config.json` into a DVARA `gateway.yaml`, with the same report. Source: [dvara-bifrost-importer](https://github.com/dvarahq/dvara-bifrost-importer) |

To keep one as a command: `jbang app install litellm-to-dvara@dvarahq` (or `bifrost-to-dvara@dvarahq`).
