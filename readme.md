## GitHub Repository Secrets

</br>

### You need to configure the following secrets in your GitHub repository:

</br>


### WORKLOAD_IDENTITY_PROVIDER: Your Workload Identity Provider name. </br>
### PROJECT_ID: Your Google Cloud project ID. </br>
### GAR_LOCATION: Your Artifact Registry location (e.g., us-central1). </br>
### GKE_CLUSTER: Your GKE cluster name. </br>
### GKE_ZONE: Your GKE zone (e.g., us-central1-c). </br>
### To set secrets, go to your repository settings > Secrets and variables > Actions.  </br>

</br>

### 6. Enable Google Cloud APIs </br>

</br>

### Ensure the following APIs are enabled:

</br>

### Artifact Registry (artifactregistry.googleapis.com)

</br>

### Google Kubernetes Engine (container.googleapis.com)

</br>

### IAM Credentials API (iamcredentials.googleapis.com)
