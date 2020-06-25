# Splunk (free) chart
helm chart for splunk free vsn. 
single splunk pod and one persistent storage.

for testing and playing :)

# usage:
 1) git clone this repo 
 2) cd the dir
 3) install 
    
    helm install -n play . --debug --dryrun 
 
 
# notes
- tested with microk8s with storage plugin enabled.
- no admin password is needed.


