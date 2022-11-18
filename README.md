Failed to create task run pod "s2i-pipeline-run-444lh-s2i-ocp-eap": 
pods "s2i-pipeline-run-444lh-s2i-ocp-eap-pod" is forbidden: unable to validate against any security context constraint:
[
  provider "anyuid": 
  Forbidden: not usable by user or serviceaccount, spec.containers[1].securityContext.privileged: 
  Invalid value: true: 
  Privileged containers are not allowed, provider "hostmount-anyuid": 
  Forbidden: not usable by user or serviceaccount, provider "elasticsearch-scc": 
  Forbidden: not usable by user or serviceaccount, provider "log-collector-scc": 
  Forbidden: not usable by user or serviceaccount, provider "machine-api-termination-handler": 
  Forbidden: not usable by user or serviceaccount, provider "hostnetwork": 
  Forbidden: not usable by user or serviceaccount, provider "hostaccess": 
  Forbidden: not usable by user or serviceaccount, provider "node-exporter": 
  Forbidden: not usable by user or serviceaccount, provider "privileged": 
  Forbidden: not usable by user or serviceaccount
]. 
Maybe missing or invalid Task <NAMESPACE>/s2i
