## hello-app-chart
### Requirements:
#### App Deployment: 
- Container Image: gcr.io/google-samples/hello-app:2.0
- Exposed Service
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
- [ ] Adjust Deployment Template with params
- [ ] Adjust Service Template
- [ ] Add Dependencies
- [ ] Add Pod deployment
- [ ] Docs
