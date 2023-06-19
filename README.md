# Fluentd


##Helm Install
helm install --name fluentd-release -f values/{project}/values-prod.yaml templates/ -n logging 

##Helm Uninstall 
helm uninstall fluentd-release -n logging
