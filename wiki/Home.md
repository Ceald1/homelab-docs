

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
       fedora server
       172.20.99.100
   }
   class Wagyl {
       16GB RAM
       250GB Storage
       2 cores and 4 threads
       fedora server
       172.20.99.101
   }
   class Kidili {
       16GB RAM
       250GB Storage
       2 cores and 4 threads
       fedora server
       172.20.99.102
   }
   class VIP {
       VIP at 172.20.100.100
   }
```



