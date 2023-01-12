# day2configuration-identity-providers

This repository has the manifest to deploy and configure Oauth resources in order to satisfies security credentials access.

## Getting start

This project has been configured with Kustomize, so to apply the manifests just simply execute the following commands:

```
oc apply -k overlays/$ENV
```

Where $ENV is the environment where you need deploy on. Notice that you might need to add changes in order to satisfies your cluster environment requirements, so that your must apply that changes on overlays environment folders instead in base manifests.

### Dev environment credentials

| User     | Password  |
|-----------|-----------|
| ocpadmin  | ocpadmin  |
| ocpreader | ocpreader |