# Azure Container App - Dapr sample

<img src="https://raw.githubusercontent.com/KamalRathnayake/Dapr-Todo-App/main/image.png" width="500" />

This sample levarages the Service-to-service invocation and State management features from Dapr.

### Instructions

1. Download code
1. Set `accountName`, `account-key` and `containerName` in `/components/statetore.yml` from your own Azure Storage account
1. Deploy `TodoApp.Backend` and `TodoApp.Frontend` as separate container apps in the same container apps environment
1. `TodoApp.Backend` is not reachable from the internet but can talk to `TodoApp.Frontend`
