# use-case-postgres
Postgres installation demo
Assignment
-------------------------------------------------

Use Case #1: 

1. Create Kubernetes cluster with high availability of master nodes(if possible) on local ( or GCP or AWS using free tier).
2. Deploy Postgres or any RDBMS database operator on Kubernetes cluster
3. Create the Postgres or any database instance deployment manifests using helm chart
4. Deploy the Postgres instance or any database (helm chart)  using any GIT-Ops tools( FluxCD/ArgoCD).



-------------------------------------------------
Solution Done
-------------------------------------------------

1. Created Kubernetes Cluster in GCP using free tier.
2. Written Kubernentes script for postgres deployment and successfully installed.
3. Created helm chart for postgres deployment and deployed on GCP kubernetes cluster.
4. Deployed the postgres instance on GCP kubernetes cluster using GIT-Ops tool ArgoCD
5. Details are available in the use_case_doc.doc.
