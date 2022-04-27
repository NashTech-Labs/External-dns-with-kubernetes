# External-dns-with-kubernetes

This template helps to deploy and setup external-dns on GKE.

Follow this blog for more information: https://blog.knoldus.com/introduction-to-external-dns-in-kubernetes/ 

Note: You should deploy your Kubernetes cluster which has following permission to the nodes: https://www.googleapis.com/auth/ndev.clouddns.readwrite

You can use below command for quick-start purpose to deploy GKE:

    gcloud container clusters create "test-external-dns" --num-nodes 2 --scopes "https://www.googleapis.com/auth/ndev.clouddns.readwrite"
