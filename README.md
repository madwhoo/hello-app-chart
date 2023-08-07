## hello-app-chart
### Requirements:
#### App Deployment: 
- Container Image: gcr.io/google-samples/hello-app:2.0
- Exposed Service and ignore during uninstall
- Deployment:
    - configurable replica
    - env variables
    - Optional PV
- Configmap with SSH public key
#### External Dependency:
- Bitnami/MySQL Chart dependency
    - Single Pod deployment

### Tasks:
- [x] Create Base-Chart
- [x] Create ssh priv/pub key
- [x] Adjust Deployment Template with params
- [x] Adjust Service Template
- [x] Add Dependencies
- [x] Readme
