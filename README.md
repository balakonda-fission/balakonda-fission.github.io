
# Prerequisites:

+ Install helm. 
Note :- Install helm by using the below link

Helm installation :- https://helm.sh/docs/intro/install/

# Steps to follow to run the helm chart 

Add the helm repositary to your local helm repo

+ helm repo add pcs-stack-repo https://balakonda-fission.github.io/charts

Check the local helm repo list

+ helm repo list

Install the helm chart

+ helm install pcs-stack pcs-stack-repo/pcs-stack