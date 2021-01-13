Shortcuts for Kubectl cli

pods 	--> list all pods in the cluster
nodes 	--> list nodes
ns	--> list namespace
dep 	--> list deployments
svc 	--> list services
ep	--> list endpoints
sc	--> list storage class
pv	--> list persistent volumes
pvc 	--> list persisent volume claim


kg <p|d|sf|r|c|s|j|e><namespace>--> list pod|deploy|deamonset|statefulset|replicaset|cm|service|job|event for the given namespace 

podssh <podname> 		--> login to pod
podexec <podname> <command> 	--> exec the given command
podel <podname> 		--> delete pod
poddelf <podname>		--> force delete pod
poddes <podname>		--> describe pod
podedit	<podname>		--> edit pod descriptor
