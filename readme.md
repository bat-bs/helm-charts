# Blue Atlas Helm Charts
To provide the best possible solutions for our Customers, we use and support many open source projects.
To install these solutions more easily and streamlining the way we install applications, we maintain Helm-Charts of applications that do not have official Charts. 

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
