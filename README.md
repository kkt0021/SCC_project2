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

Extras: the RedisCache.java file shows the changes made to the file as input for war file generation, relative to the 1st project.

Keiko Kolin Tiago k.tiago@FCT.UNL.PT

Thiago Araujo Monteiro tar.monteiro@FCT.UNL.PT
