# Blue Atlas Helm Charts

> [!WARNING]  
> This Helm Chart Repo will soon be depricated as a tweaked Version of the Librechat Chart [has been merged into Upstream](https://github.com/danny-avila/LibreChat/pull/3638)

<br />
<br />
<br />

## Breaking Changes
### 1.0.0
- Rename `librechat.config` to `librechat.configEnv`

## Getting Started

```sh
helm repo add blue-atlas https://charts.blue-atlas.de
helm install -f <values-file.yaml> blue-atlas/<chartname>
```
Available Charts:
- `librechat` - A self-hosted ChatGPT alternative with support for many LLMs plugins and other models
