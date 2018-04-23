# Sizing IBM Cloud Private

Although each ICP deployment will have its own characteristics, this is a simple T-shirt size for ICP deployment on the VMware environment.

Use it simply as a guide for your deployment, especially regarding the number of Worker nodes.

## Small ICP environment

| Node type | Number of nodes | CPU | Memory | Disk |
| --- | --- | --- | --- | --- | 
| Boot | 1 | 2 | 4 GB | 40 GB |
| Master / Management | 3 | 8 | 16 GB | 200 GB |
| Proxy | 3 | 4 | 8 GB | 40 GB |
| Worker | 3+ | 8 | 16 GB | 100 GB |
| Total | 10+ | 62 | 124 GB| 1060 GB |


## Medium ICP environment

| Node type | Number of nodes | CPU | Memory | Disk |
| --- | --- | --- | --- | --- | 
| Boot | 1 | 2 | 4 GB | 40 GB |
| Master | 3 | 8 | 16 GB | 200 GB |
| Management | 2 | 8 | 16 GB | 200 GB |
| Proxy | 3 | 4 | 8 GB | 40 GB |
| VA | 3 | 6 | 8 GB | 100 GB |
| Worker | 5+ | 8 | 16 GB | 100 GB |
| Total | 	17+ | 112  | 212 GB| 1960 GB|

## Large ICP environment

| Node type | Number of nodes | CPU | Memory | Disk |
| --- | --- | --- | --- | --- | 
| Boot | 1 | 2| 4 GB | 40 GB |
| Master | 5 | 8 | 32 GB | 200 GB |
| Management | 3 | 8 | 32 GB | 400 GB |
| Proxy | 3 | 4 | 8 GB | 40 GB |
| VA | 5 | 8 | 16 GB | 400 GB |
| Worker | 7+ | 8 | 16 GB | 100 GB |
| Total |	20+ | 138 |392 GB| 3160 GB |
