# Blue Atlas Helm Charts
To provide the best possible solutions for our Customers, we use and support many open source projects.
To install these solutions more easily and streamlining the way we install applications, we maintain Helm-Charts of applications that do not have official Charts. 

## Getting Started

```sh
helm repo add blue-atlas https://charts.blue-atlas.de
helm install -f <values-file.yaml> blue-atlas/<chartname>
```
Available Charts:
- `squest` - A Self-Service Portal on AWX maintained by HP