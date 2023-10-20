
# Deploy the application 
gcloud run services replace service.yaml
gcloud run services set-iam-policy direct-image policy.yaml