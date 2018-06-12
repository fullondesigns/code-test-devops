Ravelin Code Test For DevOps
============================

## Setup
* Provider your GCP email address to Ravelin
* Check you have access to the image
* `gcloud compute images list --project ravelin-code-test`
* Create a new image
```
create MY-INSTANCE --project MY-PROJECT --image ravelin-code-test-image --image-project ravelin-code-test --zone us-east1-a --machine-type f1-micro
```

## Problems
* Nginx not working properly. Please fix.
* Application is failing to connect to api.ravelin.com. e.g. `curl api.ravelin.com`
* CPU utilisation problem on this server, all others seem fine?
* Developer can't seem to login from Tuvalu
* Cannot connect to `https://api.github.com/`
