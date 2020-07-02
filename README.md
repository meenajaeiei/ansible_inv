
[non-prod-k8s]
Master Nodes   ansible_user=ubuntu ansible_host=10.45.42.176
Worker Nodes1 ansible_user=ubuntu ansible_host=10.45.42.177
Worker Nodes2 ansible_user=ubuntu ansible_host=10.45.42.178

[non-prod-tool]
Jira Software ansible_user=ubuntu ansible_host=10.45.42.179
GitLab ansible_user=ubuntu ansible_host=10.45.42.180
Sonatype Nexus ansible_user=ubuntu ansible_host=10.45.42.203
Jenkins Master ansible_user=ubuntu ansible_host=10.45.42.204
Jenkins Slave ansible_user=ubuntu ansible_host=10.45.42.205
Sonarqube ansible_user=ubuntu ansible_host=10.45.42.206
NFS ansible_user=ubuntu ansible_host=10.45.42.207
PostgreSQL1 ansible_user=ubuntu ansible_host=10.45.42.208
PostgreSQL2 ansible_user=ubuntu ansible_host=10.45.42.209

[non-prod]
non-prod-k8s
non-prod-tool

[prod-k8s]
Master Nodes ansible_user=ubuntu ansible_host= 10.45.41.81
Master Nodes ansible_user=ubuntu ansible_host= 10.45.41.82
Master Nodes ansible_user=ubuntu ansible_host= 10.45.41.83
Worker Nodes ansible_user=ubuntu ansible_host= 10.45.41.84
Worker Nodes ansible_user=ubuntu ansible_host= 10.45.41.85
Worker Nodes ansible_user=ubuntu ansible_host= 10.45.41.86

[prod-tool]
Sonatype Nexus ansible_user=ubuntu ansible_host= 10.45.41.87
Jenkins Master ansible_user=ubuntu ansible_host= 10.45.41.88
Jenkins Slave ansible_user=ubuntu ansible_host= 10.45.41.89
NFS ansible_user=ubuntu ansible_host= 10.45.41.90
PostgreSQL ansible_user=ubuntu ansible_host= 10.45.41.91
PostgreSQL ansible_user=ubuntu ansible_host= 10.45.41.92
PostgreSQL ansible_user=ubuntu ansible_host= 10.45.41.93

[prod]
prod-k8s
prod-tool
