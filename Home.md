

# Cluster Nodes


```mermaid
---
title: Cluster Nodes
---
classDiagram
   Zeus
   Hades
   Apollo
   VIP 
   VIP -- Zeus
   VIP -- Hades
   VIP -- Apollo
   note "longhorn storage class <br>cilium CNI + hubble<br>traefik ingress"

   class Zeus {
       16GB RAM
       250GB Storage
       2 cores and 4 threads
       opensuse
       172.20.100.101
   }
   class Hades {
       16GB RAM
       250GB Storage
       2 cores and 4 threads
       opensuse
       172.20.100.102
   }
   class Apollo {
       16GB RAM
       250GB Storage
       2 cores and 4 threads
       opensuse
       172.20.100.103
   }
   class VIP {
       VIP at 172.20.100.100
   }
```



