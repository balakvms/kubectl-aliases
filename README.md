# Shortcuts for Kube CLI

#### source podrc in bashrc file

```
pods 	--> list all pods in the cluster
nodes 	--> list all nodes
ns	--> list all namespace
dep 	--> list all deployments
ds	--> list all daemonset
rs	--> list all replicaset
jobs 	--> list all jobs
events 	--> list all events
svc 	--> list all services
ep	--> list all endpoints
sc	--> list all storage class
pv	--> list all persistent volumes
pvc 	--> list all persisent volume claim

kg <p|d|ds|ss|rs|c|s|j|e> <namespace>--> list pod|deploy|deamonset|statefulset|replicaset|cm|service|job|event for the given namespace 
kd <p|d|ds|ss|rs|c|s|j|e> <name>--> describe pod|deploy|deamonset|statefulset|replicaset|cm|service|job|event for the given name 

podssh <podname> 		--> login to pod
podexec <podname> <command> 	--> exec the given command
podel <podname> 		--> delete pod
poddelf <podname>		--> force delete pod
poddes <podname>		--> describe pod
podedit	<podname>		--> edit pod descriptor
```
