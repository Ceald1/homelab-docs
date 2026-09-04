

# Cluster Nodes


```mermaid
---
title: Cluster Nodes
---
classDiagram
   Baiame
   Wagyl
   Kidili
   VIP 
   VIP -- Baiame
   VIP -- Wagyl
   VIP -- Kidili
   note "longhorn storage class <br>cilium CNI + hubble<br>traefik ingress"

   class Baiame {
       16GB RAM
       250GB Storage
       2 cores and 4 threads
       opensuse
       172.20.100.101
   }
   class Wagyl {
       16GB RAM
       250GB Storage
       2 cores and 4 threads
       opensuse
       172.20.100.102
   }
   class Kidili {
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



