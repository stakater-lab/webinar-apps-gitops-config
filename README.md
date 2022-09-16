# nordmart-gitops

GitOps config will contain Tenant Applications, ArgoCD Apps, Tekton Pipelines.

### Get Started
Add following folders to the repo.

- **For Each Application**
This folder will contain application helm chart which will be updated with newly built image whenever main of application repo is updated. 
- **For Tekton Manifests**
This folder will contain the pipeline to be run for application.
- **For ArgoCD Apps**
The folder contains argocd applications for all applications & pipelines.