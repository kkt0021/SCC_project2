# SCC_project2

To build

-> az aks get-credentials --resource-group scc2223-rg-westeurope-65013 --name my-scc2223-cluster-65013
<br/>
--(First time only)

-> kubectl apply -f azure-vote.yaml
<br/>
<br/>
<br/>
<br/>
To use, get azure-ebay-front EXTERNAL-IP with:

-> kubectl get services

and access using {EXTERNAL-IP}/SCC_EBay-1.0/
