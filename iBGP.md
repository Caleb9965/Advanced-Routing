# CORE-EDGE
```
router bgp 65501
 bgp router-id 10.255.37.1
 bgp log-neighbor-changes
 network 0.0.0.0 mask 0.0.0.0
 !
 neighbor 10.255.37.2 remote-as 65501
 neighbor 10.255.37.2 update-source Loopback0
 neighbor 10.255.37.2 soft-reconfiguration inbound
 neighbor 10.255.37.2 next-hop-self
 !
 neighbor 10.255.37.3 remote-as 65501
 neighbor 10.255.37.3 update-source Loopback0
 neighbor 10.255.37.3 soft-reconfiguration inbound
 neighbor 10.255.37.3 next-hop-self
 !
 neighbor 10.255.37.4 remote-as 65501
 neighbor 10.255.37.4 update-source Loopback0
 neighbor 10.255.37.4 soft-reconfiguration inbound
 neighbor 10.255.37.4 next-hop-self
 !
 neighbor 10.255.37.5 remote-as 65501
 neighbor 10.255.37.5 update-source Loopback0
 neighbor 10.255.37.5 soft-reconfiguration inbound
 neighbor 10.255.37.5 next-hop-self
 !
 neighbor 10.255.37.6 remote-as 65501
 neighbor 10.255.37.6 update-source Loopback0
 neighbor 10.255.37.6 soft-reconfiguration inbound
 neighbor 10.255.37.6 next-hop-self
 !
 neighbor 10.255.37.7 remote-as 65501
 neighbor 10.255.37.7 update-source Loopback0
 neighbor 10.255.37.7 soft-reconfiguration inbound
 neighbor 10.255.37.7 next-hop-self
 !
 neighbor 10.255.37.8 remote-as 65501
 neighbor 10.255.37.8 update-source Loopback0
 neighbor 10.255.37.8 soft-reconfiguration inbound
 neighbor 10.255.37.8 next-hop-self
 !
 neighbor 10.255.37.9 remote-as 65501
 neighbor 10.255.37.9 update-source Loopback0
 neighbor 10.255.37.9 soft-reconfiguration inbound
 neighbor 10.255.37.9 next-hop-self
 !
 neighbor 10.255.37.10 remote-as 65501
 neighbor 10.255.37.10 update-source Loopback0
 neighbor 10.255.37.10 soft-reconfiguration inbound
 neighbor 10.255.37.10 next-hop-self
 !
 neighbor 10.255.37.11 remote-as 65501
 neighbor 10.255.37.11 update-source Loopback0
 neighbor 10.255.37.11 soft-reconfiguration inbound
 neighbor 10.255.37.11 next-hop-self
 !
 neighbor 10.255.37.12 remote-as 65501
 neighbor 10.255.37.12 update-source Loopback0
 neighbor 10.255.37.12 soft-reconfiguration inbound
 neighbor 10.255.37.12 next-hop-self
 !
 neighbor 10.255.37.13 remote-as 65501
 neighbor 10.255.37.13 update-source Loopback0
 neighbor 10.255.37.13 soft-reconfiguration inbound
 neighbor 10.255.37.13 next-hop-self
 !
 neighbor 10.255.37.14 remote-as 65501
 neighbor 10.255.37.14 update-source Loopback0
 neighbor 10.255.37.14 soft-reconfiguration inbound
 neighbor 10.255.37.14 next-hop-self
```

---
# BB-RTR-1 
```
router bgp 65501
 bgp router-id 10.255.37.2
 bgp log-neighbor-changes
 !
 neighbor 10.255.37.1 remote-as 65501
 neighbor 10.255.37.1 update-source Loopback0
 neighbor 10.255.37.1 soft-reconfiguration inbound
 neighbor 10.255.37.1 next-hop-self
 !
 neighbor 10.255.37.3 remote-as 65501
 neighbor 10.255.37.3 update-source Loopback0
 neighbor 10.255.37.3 soft-reconfiguration inbound
 neighbor 10.255.37.3 next-hop-self
 !
 neighbor 10.255.37.4 remote-as 65501
 neighbor 10.255.37.4 update-source Loopback0
 neighbor 10.255.37.4 soft-reconfiguration inbound
 neighbor 10.255.37.4 next-hop-self
 !
 neighbor 10.255.37.5 remote-as 65501
 neighbor 10.255.37.5 update-source Loopback0
 neighbor 10.255.37.5 soft-reconfiguration inbound
 neighbor 10.255.37.5 next-hop-self
 !
 neighbor 10.255.37.6 remote-as 65501
 neighbor 10.255.37.6 update-source Loopback0
 neighbor 10.255.37.6 soft-reconfiguration inbound
 neighbor 10.255.37.6 next-hop-self
 !
 neighbor 10.255.37.7 remote-as 65501
 neighbor 10.255.37.7 update-source Loopback0
 neighbor 10.255.37.7 soft-reconfiguration inbound
 neighbor 10.255.37.7 next-hop-self
 !
 neighbor 10.255.37.8 remote-as 65501
 neighbor 10.255.37.8 update-source Loopback0
 neighbor 10.255.37.8 soft-reconfiguration inbound
 neighbor 10.255.37.8 next-hop-self
 !
 neighbor 10.255.37.9 remote-as 65501
 neighbor 10.255.37.9 update-source Loopback0
 neighbor 10.255.37.9 soft-reconfiguration inbound
 neighbor 10.255.37.9 next-hop-self
 !
 neighbor 10.255.37.10 remote-as 65501
 neighbor 10.255.37.10 update-source Loopback0
 neighbor 10.255.37.10 soft-reconfiguration inbound
 neighbor 10.255.37.10 next-hop-self
 !
 neighbor 10.255.37.11 remote-as 65501
 neighbor 10.255.37.11 update-source Loopback0
 neighbor 10.255.37.11 soft-reconfiguration inbound
 neighbor 10.255.37.11 next-hop-self
 !
 neighbor 10.255.37.12 remote-as 65501
 neighbor 10.255.37.12 update-source Loopback0
 neighbor 10.255.37.12 soft-reconfiguration inbound
 neighbor 10.255.37.12 next-hop-self
 !
 neighbor 10.255.37.13 remote-as 65501
 neighbor 10.255.37.13 update-source Loopback0
 neighbor 10.255.37.13 soft-reconfiguration inbound
 neighbor 10.255.37.13 next-hop-self
 !
 neighbor 10.255.37.14 remote-as 65501
 neighbor 10.255.37.14 update-source Loopback0
 neighbor 10.255.37.14 soft-reconfiguration inbound
 neighbor 10.255.37.14 next-hop-self
```

---
# BB-RTR-2
```
router bgp 65501
 bgp router-id 10.255.37.3
 bgp log-neighbor-changes
 !
 neighbor 10.255.37.1 remote-as 65501
 neighbor 10.255.37.1 update-source Loopback0
 neighbor 10.255.37.1 soft-reconfiguration inbound
 neighbor 10.255.37.1 next-hop-self
 !
 neighbor 10.255.37.2 remote-as 65501
 neighbor 10.255.37.2 update-source Loopback0
 neighbor 10.255.37.2 soft-reconfiguration inbound
 neighbor 10.255.37.2 next-hop-self
 !
 neighbor 10.255.37.4 remote-as 65501
 neighbor 10.255.37.4 update-source Loopback0
 neighbor 10.255.37.4 soft-reconfiguration inbound
 neighbor 10.255.37.4 next-hop-self
 !
 neighbor 10.255.37.5 remote-as 65501
 neighbor 10.255.37.5 update-source Loopback0
 neighbor 10.255.37.5 soft-reconfiguration inbound
 neighbor 10.255.37.5 next-hop-self
 !
 neighbor 10.255.37.6 remote-as 65501
 neighbor 10.255.37.6 update-source Loopback0
 neighbor 10.255.37.6 soft-reconfiguration inbound
 neighbor 10.255.37.6 next-hop-self
 !
 neighbor 10.255.37.7 remote-as 65501
 neighbor 10.255.37.7 update-source Loopback0
 neighbor 10.255.37.7 soft-reconfiguration inbound
 neighbor 10.255.37.7 next-hop-self
 !
 neighbor 10.255.37.8 remote-as 65501
 neighbor 10.255.37.8 update-source Loopback0
 neighbor 10.255.37.8 soft-reconfiguration inbound
 neighbor 10.255.37.8 next-hop-self
 !
 neighbor 10.255.37.9 remote-as 65501
 neighbor 10.255.37.9 update-source Loopback0
 neighbor 10.255.37.9 soft-reconfiguration inbound
 neighbor 10.255.37.9 next-hop-self
 !
 neighbor 10.255.37.10 remote-as 65501
 neighbor 10.255.37.10 update-source Loopback0
 neighbor 10.255.37.10 soft-reconfiguration inbound
 neighbor 10.255.37.10 next-hop-self
 !
 neighbor 10.255.37.11 remote-as 65501
 neighbor 10.255.37.11 update-source Loopback0
 neighbor 10.255.37.11 soft-reconfiguration inbound
 neighbor 10.255.37.11 next-hop-self
 !
 neighbor 10.255.37.12 remote-as 65501
 neighbor 10.255.37.12 update-source Loopback0
 neighbor 10.255.37.12 soft-reconfiguration inbound
 neighbor 10.255.37.12 next-hop-self
 !
 neighbor 10.255.37.13 remote-as 65501
 neighbor 10.255.37.13 update-source Loopback0
 neighbor 10.255.37.13 soft-reconfiguration inbound
 neighbor 10.255.37.13 next-hop-self
 !
 neighbor 10.255.37.14 remote-as 65501
 neighbor 10.255.37.14 update-source Loopback0
 neighbor 10.255.37.14 soft-reconfiguration inbound
 neighbor 10.255.37.14 next-hop-self
```

---
# BB-RTR-3 
```
router bgp 65501
 bgp router-id 10.255.37.4
 bgp log-neighbor-changes
 !
 neighbor 10.255.37.1 remote-as 65501
 neighbor 10.255.37.1 update-source Loopback0
 neighbor 10.255.37.1 soft-reconfiguration inbound
 neighbor 10.255.37.1 next-hop-self
 !
 neighbor 10.255.37.2 remote-as 65501
 neighbor 10.255.37.2 update-source Loopback0
 neighbor 10.255.37.2 soft-reconfiguration inbound
 neighbor 10.255.37.2 next-hop-self
 !
 neighbor 10.255.37.3 remote-as 65501
 neighbor 10.255.37.3 update-source Loopback0
 neighbor 10.255.37.3 soft-reconfiguration inbound
 neighbor 10.255.37.3 next-hop-self
 !
 neighbor 10.255.37.5 remote-as 65501
 neighbor 10.255.37.5 update-source Loopback0
 neighbor 10.255.37.5 soft-reconfiguration inbound
 neighbor 10.255.37.5 next-hop-self
 !
 neighbor 10.255.37.6 remote-as 65501
 neighbor 10.255.37.6 update-source Loopback0
 neighbor 10.255.37.6 soft-reconfiguration inbound
 neighbor 10.255.37.6 next-hop-self
 !
 neighbor 10.255.37.7 remote-as 65501
 neighbor 10.255.37.7 update-source Loopback0
 neighbor 10.255.37.7 soft-reconfiguration inbound
 neighbor 10.255.37.7 next-hop-self
 !
 neighbor 10.255.37.8 remote-as 65501
 neighbor 10.255.37.8 update-source Loopback0
 neighbor 10.255.37.8 soft-reconfiguration inbound
 neighbor 10.255.37.8 next-hop-self
 !
 neighbor 10.255.37.9 remote-as 65501
 neighbor 10.255.37.9 update-source Loopback0
 neighbor 10.255.37.9 soft-reconfiguration inbound
 neighbor 10.255.37.9 next-hop-self
 !
 neighbor 10.255.37.10 remote-as 65501
 neighbor 10.255.37.10 update-source Loopback0
 neighbor 10.255.37.10 soft-reconfiguration inbound
 neighbor 10.255.37.10 next-hop-self
 !
 neighbor 10.255.37.11 remote-as 65501
 neighbor 10.255.37.11 update-source Loopback0
 neighbor 10.255.37.11 soft-reconfiguration inbound
 neighbor 10.255.37.11 next-hop-self
 !
 neighbor 10.255.37.12 remote-as 65501
 neighbor 10.255.37.12 update-source Loopback0
 neighbor 10.255.37.12 soft-reconfiguration inbound
 neighbor 10.255.37.12 next-hop-self
 !
 neighbor 10.255.37.13 remote-as 65501
 neighbor 10.255.37.13 update-source Loopback0
 neighbor 10.255.37.13 soft-reconfiguration inbound
 neighbor 10.255.37.13 next-hop-self
 !
 neighbor 10.255.37.14 remote-as 65501
 neighbor 10.255.37.14 update-source Loopback0
 neighbor 10.255.37.14 soft-reconfiguration inbound
 neighbor 10.255.37.14 next-hop-self
```

---
# BB-RTR-4  
```
router bgp 65501
 bgp router-id 10.255.37.5
 bgp log-neighbor-changes
 !
 neighbor 10.255.37.1 remote-as 65501
 neighbor 10.255.37.1 update-source Loopback0
 neighbor 10.255.37.1 soft-reconfiguration inbound
 neighbor 10.255.37.1 next-hop-self
 !
 neighbor 10.255.37.2 remote-as 65501
 neighbor 10.255.37.2 update-source Loopback0
 neighbor 10.255.37.2 soft-reconfiguration inbound
 neighbor 10.255.37.2 next-hop-self
 !
 neighbor 10.255.37.3 remote-as 65501
 neighbor 10.255.37.3 update-source Loopback0
 neighbor 10.255.37.3 soft-reconfiguration inbound
 neighbor 10.255.37.3 next-hop-self
 !
 neighbor 10.255.37.4 remote-as 65501
 neighbor 10.255.37.4 update-source Loopback0
 neighbor 10.255.37.4 soft-reconfiguration inbound
 neighbor 10.255.37.4 next-hop-self
 !
 neighbor 10.255.37.6 remote-as 65501
 neighbor 10.255.37.6 update-source Loopback0
 neighbor 10.255.37.6 soft-reconfiguration inbound
 neighbor 10.255.37.6 next-hop-self
 !
 neighbor 10.255.37.7 remote-as 65501
 neighbor 10.255.37.7 update-source Loopback0
 neighbor 10.255.37.7 soft-reconfiguration inbound
 neighbor 10.255.37.7 next-hop-self
 !
 neighbor 10.255.37.8 remote-as 65501
 neighbor 10.255.37.8 update-source Loopback0
 neighbor 10.255.37.8 soft-reconfiguration inbound
 neighbor 10.255.37.8 next-hop-self
 !
 neighbor 10.255.37.9 remote-as 65501
 neighbor 10.255.37.9 update-source Loopback0
 neighbor 10.255.37.9 soft-reconfiguration inbound
 neighbor 10.255.37.9 next-hop-self
 !
 neighbor 10.255.37.10 remote-as 65501
 neighbor 10.255.37.10 update-source Loopback0
 neighbor 10.255.37.10 soft-reconfiguration inbound
 neighbor 10.255.37.10 next-hop-self
 !
 neighbor 10.255.37.11 remote-as 65501
 neighbor 10.255.37.11 update-source Loopback0
 neighbor 10.255.37.11 soft-reconfiguration inbound
 neighbor 10.255.37.11 next-hop-self
 !
 neighbor 10.255.37.12 remote-as 65501
 neighbor 10.255.37.12 update-source Loopback0
 neighbor 10.255.37.12 soft-reconfiguration inbound
 neighbor 10.255.37.12 next-hop-self
 !
 neighbor 10.255.37.13 remote-as 65501
 neighbor 10.255.37.13 update-source Loopback0
 neighbor 10.255.37.13 soft-reconfiguration inbound
 neighbor 10.255.37.13 next-hop-self
 !
 neighbor 10.255.37.14 remote-as 65501
 neighbor 10.255.37.14 update-source Loopback0
 neighbor 10.255.37.14 soft-reconfiguration inbound
 neighbor 10.255.37.14 next-hop-self
```

---
# BB-RTR-5  
```
router bgp 65501
 bgp router-id 10.255.37.6
 bgp log-neighbor-changes
 !
 neighbor 10.255.37.1 remote-as 65501
 neighbor 10.255.37.1 update-source Loopback0
 neighbor 10.255.37.1 soft-reconfiguration inbound
 neighbor 10.255.37.1 next-hop-self
 !
 neighbor 10.255.37.2 remote-as 65501
 neighbor 10.255.37.2 update-source Loopback0
 neighbor 10.255.37.2 soft-reconfiguration inbound
 neighbor 10.255.37.2 next-hop-self
 !
 neighbor 10.255.37.3 remote-as 65501
 neighbor 10.255.37.3 update-source Loopback0
 neighbor 10.255.37.3 soft-reconfiguration inbound
 neighbor 10.255.37.3 next-hop-self
 !
 neighbor 10.255.37.4 remote-as 65501
 neighbor 10.255.37.4 update-source Loopback0
 neighbor 10.255.37.4 soft-reconfiguration inbound
 neighbor 10.255.37.4 next-hop-self
 !
 neighbor 10.255.37.5 remote-as 65501
 neighbor 10.255.37.5 update-source Loopback0
 neighbor 10.255.37.5 soft-reconfiguration inbound
 neighbor 10.255.37.5 next-hop-self
 !
 neighbor 10.255.37.7 remote-as 65501
 neighbor 10.255.37.7 update-source Loopback0
 neighbor 10.255.37.7 soft-reconfiguration inbound
 neighbor 10.255.37.7 next-hop-self
 !
 neighbor 10.255.37.8 remote-as 65501
 neighbor 10.255.37.8 update-source Loopback0
 neighbor 10.255.37.8 soft-reconfiguration inbound
 neighbor 10.255.37.8 next-hop-self
 !
 neighbor 10.255.37.9 remote-as 65501
 neighbor 10.255.37.9 update-source Loopback0
 neighbor 10.255.37.9 soft-reconfiguration inbound
 neighbor 10.255.37.9 next-hop-self
 !
 neighbor 10.255.37.10 remote-as 65501
 neighbor 10.255.37.10 update-source Loopback0
 neighbor 10.255.37.10 soft-reconfiguration inbound
 neighbor 10.255.37.10 next-hop-self
 !
 neighbor 10.255.37.11 remote-as 65501
 neighbor 10.255.37.11 update-source Loopback0
 neighbor 10.255.37.11 soft-reconfiguration inbound
 neighbor 10.255.37.11 next-hop-self
 !
 neighbor 10.255.37.12 remote-as 65501
 neighbor 10.255.37.12 update-source Loopback0
 neighbor 10.255.37.12 soft-reconfiguration inbound
 neighbor 10.255.37.12 next-hop-self
 !
 neighbor 10.255.37.13 remote-as 65501
 neighbor 10.255.37.13 update-source Loopback0
 neighbor 10.255.37.13 soft-reconfiguration inbound
 neighbor 10.255.37.13 next-hop-self
 !
 neighbor 10.255.37.14 remote-as 65501
 neighbor 10.255.37.14 update-source Loopback0
 neighbor 10.255.37.14 soft-reconfiguration inbound
 neighbor 10.255.37.14 next-hop-self
```

---
# LR-AR1-1 
```
router bgp 65501
 bgp router-id 10.255.37.7
 bgp log-neighbor-changes
 !
 neighbor 10.255.37.1 remote-as 65501
 neighbor 10.255.37.1 update-source Loopback0
 neighbor 10.255.37.1 soft-reconfiguration inbound
 neighbor 10.255.37.1 next-hop-self
 !
 neighbor 10.255.37.2 remote-as 65501
 neighbor 10.255.37.2 update-source Loopback0
 neighbor 10.255.37.2 soft-reconfiguration inbound
 neighbor 10.255.37.2 next-hop-self
 !
 neighbor 10.255.37.3 remote-as 65501
 neighbor 10.255.37.3 update-source Loopback0
 neighbor 10.255.37.3 soft-reconfiguration inbound
 neighbor 10.255.37.3 next-hop-self
 !
 neighbor 10.255.37.4 remote-as 65501
 neighbor 10.255.37.4 update-source Loopback0
 neighbor 10.255.37.4 soft-reconfiguration inbound
 neighbor 10.255.37.4 next-hop-self
 !
 neighbor 10.255.37.5 remote-as 65501
 neighbor 10.255.37.5 update-source Loopback0
 neighbor 10.255.37.5 soft-reconfiguration inbound
 neighbor 10.255.37.5 next-hop-self
 !
 neighbor 10.255.37.6 remote-as 65501
 neighbor 10.255.37.6 update-source Loopback0
 neighbor 10.255.37.6 soft-reconfiguration inbound
 neighbor 10.255.37.6 next-hop-self
 !
 neighbor 10.255.37.8 remote-as 65501
 neighbor 10.255.37.8 update-source Loopback0
 neighbor 10.255.37.8 soft-reconfiguration inbound
 neighbor 10.255.37.8 next-hop-self
 !
 neighbor 10.255.37.9 remote-as 65501
 neighbor 10.255.37.9 update-source Loopback0
 neighbor 10.255.37.9 soft-reconfiguration inbound
 neighbor 10.255.37.9 next-hop-self
 !
 neighbor 10.255.37.10 remote-as 65501
 neighbor 10.255.37.10 update-source Loopback0
 neighbor 10.255.37.10 soft-reconfiguration inbound
 neighbor 10.255.37.10 next-hop-self
 !
 neighbor 10.255.37.11 remote-as 65501
 neighbor 10.255.37.11 update-source Loopback0
 neighbor 10.255.37.11 soft-reconfiguration inbound
 neighbor 10.255.37.11 next-hop-self
 !
 neighbor 10.255.37.12 remote-as 65501
 neighbor 10.255.37.12 update-source Loopback0
 neighbor 10.255.37.12 soft-reconfiguration inbound
 neighbor 10.255.37.12 next-hop-self
 !
 neighbor 10.255.37.13 remote-as 65501
 neighbor 10.255.37.13 update-source Loopback0
 neighbor 10.255.37.13 soft-reconfiguration inbound
 neighbor 10.255.37.13 next-hop-self
 !
 neighbor 10.255.37.14 remote-as 65501
 neighbor 10.255.37.14 update-source Loopback0
 neighbor 10.255.37.14 soft-reconfiguration inbound
 neighbor 10.255.37.14 next-hop-self
```

---
# LR-AR1-2  
```
router bgp 65501
 bgp router-id 10.255.37.8
 bgp log-neighbor-changes
 !
 neighbor 10.255.37.1 remote-as 65501
 neighbor 10.255.37.1 update-source Loopback0
 neighbor 10.255.37.1 soft-reconfiguration inbound
 neighbor 10.255.37.1 next-hop-self
 !
 neighbor 10.255.37.2 remote-as 65501
 neighbor 10.255.37.2 update-source Loopback0
 neighbor 10.255.37.2 soft-reconfiguration inbound
 neighbor 10.255.37.2 next-hop-self
 !
 neighbor 10.255.37.3 remote-as 65501
 neighbor 10.255.37.3 update-source Loopback0
 neighbor 10.255.37.3 soft-reconfiguration inbound
 neighbor 10.255.37.3 next-hop-self
 !
 neighbor 10.255.37.4 remote-as 65501
 neighbor 10.255.37.4 update-source Loopback0
 neighbor 10.255.37.4 soft-reconfiguration inbound
 neighbor 10.255.37.4 next-hop-self
 !
 neighbor 10.255.37.5 remote-as 65501
 neighbor 10.255.37.5 update-source Loopback0
 neighbor 10.255.37.5 soft-reconfiguration inbound
 neighbor 10.255.37.5 next-hop-self
 !
 neighbor 10.255.37.6 remote-as 65501
 neighbor 10.255.37.6 update-source Loopback0
 neighbor 10.255.37.6 soft-reconfiguration inbound
 neighbor 10.255.37.6 next-hop-self
 !
 neighbor 10.255.37.7 remote-as 65501
 neighbor 10.255.37.7 update-source Loopback0
 neighbor 10.255.37.7 soft-reconfiguration inbound
 neighbor 10.255.37.7 next-hop-self
 !
 neighbor 10.255.37.9 remote-as 65501
 neighbor 10.255.37.9 update-source Loopback0
 neighbor 10.255.37.9 soft-reconfiguration inbound
 neighbor 10.255.37.9 next-hop-self
 !
 neighbor 10.255.37.10 remote-as 65501
 neighbor 10.255.37.10 update-source Loopback0
 neighbor 10.255.37.10 soft-reconfiguration inbound
 neighbor 10.255.37.10 next-hop-self
 !
 neighbor 10.255.37.11 remote-as 65501
 neighbor 10.255.37.11 update-source Loopback0
 neighbor 10.255.37.11 soft-reconfiguration inbound
 neighbor 10.255.37.11 next-hop-self
 !
 neighbor 10.255.37.12 remote-as 65501
 neighbor 10.255.37.12 update-source Loopback0
 neighbor 10.255.37.12 soft-reconfiguration inbound
 neighbor 10.255.37.12 next-hop-self
 !
 neighbor 10.255.37.13 remote-as 65501
 neighbor 10.255.37.13 update-source Loopback0
 neighbor 10.255.37.13 soft-reconfiguration inbound
 neighbor 10.255.37.13 next-hop-self
 !
 neighbor 10.255.37.14 remote-as 65501
 neighbor 10.255.37.14 update-source Loopback0
 neighbor 10.255.37.14 soft-reconfiguration inbound
 neighbor 10.255.37.14 next-hop-self
```

---
# LR-AR2-1 
```
router bgp 65501
 bgp router-id 10.255.37.9
 bgp log-neighbor-changes
 !
 neighbor 10.255.37.1 remote-as 65501
 neighbor 10.255.37.1 update-source Loopback0
 neighbor 10.255.37.1 soft-reconfiguration inbound
 neighbor 10.255.37.1 next-hop-self
 !
 neighbor 10.255.37.2 remote-as 65501
 neighbor 10.255.37.2 update-source Loopback0
 neighbor 10.255.37.2 soft-reconfiguration inbound
 neighbor 10.255.37.2 next-hop-self
 !
 neighbor 10.255.37.3 remote-as 65501
 neighbor 10.255.37.3 update-source Loopback0
 neighbor 10.255.37.3 soft-reconfiguration inbound
 neighbor 10.255.37.3 next-hop-self
 !
 neighbor 10.255.37.4 remote-as 65501
 neighbor 10.255.37.4 update-source Loopback0
 neighbor 10.255.37.4 soft-reconfiguration inbound
 neighbor 10.255.37.4 next-hop-self
 !
 neighbor 10.255.37.5 remote-as 65501
 neighbor 10.255.37.5 update-source Loopback0
 neighbor 10.255.37.5 soft-reconfiguration inbound
 neighbor 10.255.37.5 next-hop-self
 !
 neighbor 10.255.37.6 remote-as 65501
 neighbor 10.255.37.6 update-source Loopback0
 neighbor 10.255.37.6 soft-reconfiguration inbound
 neighbor 10.255.37.6 next-hop-self
 !
 neighbor 10.255.37.7 remote-as 65501
 neighbor 10.255.37.7 update-source Loopback0
 neighbor 10.255.37.7 soft-reconfiguration inbound
 neighbor 10.255.37.7 next-hop-self
 !
 neighbor 10.255.37.8 remote-as 65501
 neighbor 10.255.37.8 update-source Loopback0
 neighbor 10.255.37.8 soft-reconfiguration inbound
 neighbor 10.255.37.8 next-hop-self
 !
 neighbor 10.255.37.10 remote-as 65501
 neighbor 10.255.37.10 update-source Loopback0
 neighbor 10.255.37.10 soft-reconfiguration inbound
 neighbor 10.255.37.10 next-hop-self
 !
 neighbor 10.255.37.11 remote-as 65501
 neighbor 10.255.37.11 update-source Loopback0
 neighbor 10.255.37.11 soft-reconfiguration inbound
 neighbor 10.255.37.11 next-hop-self
 !
 neighbor 10.255.37.12 remote-as 65501
 neighbor 10.255.37.12 update-source Loopback0
 neighbor 10.255.37.12 soft-reconfiguration inbound
 neighbor 10.255.37.12 next-hop-self
 !
 neighbor 10.255.37.13 remote-as 65501
 neighbor 10.255.37.13 update-source Loopback0
 neighbor 10.255.37.13 soft-reconfiguration inbound
 neighbor 10.255.37.13 next-hop-self
 !
 neighbor 10.255.37.14 remote-as 65501
 neighbor 10.255.37.14 update-source Loopback0
 neighbor 10.255.37.14 soft-reconfiguration inbound
 neighbor 10.255.37.14 next-hop-self
```

---
# LR-AR2-2
```
router bgp 65501
 bgp router-id 10.255.37.10
 bgp log-neighbor-changes
 !
 neighbor 10.255.37.1 remote-as 65501
 neighbor 10.255.37.1 update-source Loopback0
 neighbor 10.255.37.1 soft-reconfiguration inbound
 neighbor 10.255.37.1 next-hop-self
 !
 neighbor 10.255.37.2 remote-as 65501
 neighbor 10.255.37.2 update-source Loopback0
 neighbor 10.255.37.2 soft-reconfiguration inbound
 neighbor 10.255.37.2 next-hop-self
 !
 neighbor 10.255.37.3 remote-as 65501
 neighbor 10.255.37.3 update-source Loopback0
 neighbor 10.255.37.3 soft-reconfiguration inbound
 neighbor 10.255.37.3 next-hop-self
 !
 neighbor 10.255.37.4 remote-as 65501
 neighbor 10.255.37.4 update-source Loopback0
 neighbor 10.255.37.4 soft-reconfiguration inbound
 neighbor 10.255.37.4 next-hop-self
 !
 neighbor 10.255.37.5 remote-as 65501
 neighbor 10.255.37.5 update-source Loopback0
 neighbor 10.255.37.5 soft-reconfiguration inbound
 neighbor 10.255.37.5 next-hop-self
 !
 neighbor 10.255.37.6 remote-as 65501
 neighbor 10.255.37.6 update-source Loopback0
 neighbor 10.255.37.6 soft-reconfiguration inbound
 neighbor 10.255.37.6 next-hop-self
 !
 neighbor 10.255.37.7 remote-as 65501
 neighbor 10.255.37.7 update-source Loopback0
 neighbor 10.255.37.7 soft-reconfiguration inbound
 neighbor 10.255.37.7 next-hop-self
 !
 neighbor 10.255.37.8 remote-as 65501
 neighbor 10.255.37.8 update-source Loopback0
 neighbor 10.255.37.8 soft-reconfiguration inbound
 neighbor 10.255.37.8 next-hop-self
 !
 neighbor 10.255.37.9 remote-as 65501
 neighbor 10.255.37.9 update-source Loopback0
 neighbor 10.255.37.9 soft-reconfiguration inbound
 neighbor 10.255.37.9 next-hop-self
 !
 neighbor 10.255.37.11 remote-as 65501
 neighbor 10.255.37.11 update-source Loopback0
 neighbor 10.255.37.11 soft-reconfiguration inbound
 neighbor 10.255.37.11 next-hop-self
 !
 neighbor 10.255.37.12 remote-as 65501
 neighbor 10.255.37.12 update-source Loopback0
 neighbor 10.255.37.12 soft-reconfiguration inbound
 neighbor 10.255.37.12 next-hop-self
 !
 neighbor 10.255.37.13 remote-as 65501
 neighbor 10.255.37.13 update-source Loopback0
 neighbor 10.255.37.13 soft-reconfiguration inbound
 neighbor 10.255.37.13 next-hop-self
 !
 neighbor 10.255.37.14 remote-as 65501
 neighbor 10.255.37.14 update-source Loopback0
 neighbor 10.255.37.14 soft-reconfiguration inbound
 neighbor 10.255.37.14 next-hop-self
```

---
# LR-AR3-1 
```
router bgp 65501
 bgp router-id 10.255.37.11
 bgp log-neighbor-changes
 !
 neighbor 10.255.37.1 remote-as 65501
 neighbor 10.255.37.1 update-source Loopback0
 neighbor 10.255.37.1 soft-reconfiguration inbound
 neighbor 10.255.37.1 next-hop-self
 !
 neighbor 10.255.37.2 remote-as 65501
 neighbor 10.255.37.2 update-source Loopback0
 neighbor 10.255.37.2 soft-reconfiguration inbound
 neighbor 10.255.37.2 next-hop-self
 !
 neighbor 10.255.37.3 remote-as 65501
 neighbor 10.255.37.3 update-source Loopback0
 neighbor 10.255.37.3 soft-reconfiguration inbound
 neighbor 10.255.37.3 next-hop-self
 !
 neighbor 10.255.37.4 remote-as 65501
 neighbor 10.255.37.4 update-source Loopback0
 neighbor 10.255.37.4 soft-reconfiguration inbound
 neighbor 10.255.37.4 next-hop-self
 !
 neighbor 10.255.37.5 remote-as 65501
 neighbor 10.255.37.5 update-source Loopback0
 neighbor 10.255.37.5 soft-reconfiguration inbound
 neighbor 10.255.37.5 next-hop-self
 !
 neighbor 10.255.37.6 remote-as 65501
 neighbor 10.255.37.6 update-source Loopback0
 neighbor 10.255.37.6 soft-reconfiguration inbound
 neighbor 10.255.37.6 next-hop-self
 !
 neighbor 10.255.37.7 remote-as 65501
 neighbor 10.255.37.7 update-source Loopback0
 neighbor 10.255.37.7 soft-reconfiguration inbound
 neighbor 10.255.37.7 next-hop-self
 !
 neighbor 10.255.37.8 remote-as 65501
 neighbor 10.255.37.8 update-source Loopback0
 neighbor 10.255.37.8 soft-reconfiguration inbound
 neighbor 10.255.37.8 next-hop-self
 !
 neighbor 10.255.37.9 remote-as 65501
 neighbor 10.255.37.9 update-source Loopback0
 neighbor 10.255.37.9 soft-reconfiguration inbound
 neighbor 10.255.37.9 next-hop-self
 !
 neighbor 10.255.37.10 remote-as 65501
 neighbor 10.255.37.10 update-source Loopback0
 neighbor 10.255.37.10 soft-reconfiguration inbound
 neighbor 10.255.37.10 next-hop-self
 !
 neighbor 10.255.37.12 remote-as 65501
 neighbor 10.255.37.12 update-source Loopback0
 neighbor 10.255.37.12 soft-reconfiguration inbound
 neighbor 10.255.37.12 next-hop-self
 !
 neighbor 10.255.37.13 remote-as 65501
 neighbor 10.255.37.13 update-source Loopback0
 neighbor 10.255.37.13 soft-reconfiguration inbound
 neighbor 10.255.37.13 next-hop-self
 !
 neighbor 10.255.37.14 remote-as 65501
 neighbor 10.255.37.14 update-source Loopback0
 neighbor 10.255.37.14 soft-reconfiguration inbound
 neighbor 10.255.37.14 next-hop-self
```

---
# LR-AR3-2 
```
router bgp 65501
 bgp router-id 10.255.37.12
 bgp log-neighbor-changes
 !
 neighbor 10.255.37.1 remote-as 65501
 neighbor 10.255.37.1 update-source Loopback0
 neighbor 10.255.37.1 soft-reconfiguration inbound
 neighbor 10.255.37.1 next-hop-self
 !
 neighbor 10.255.37.2 remote-as 65501
 neighbor 10.255.37.2 update-source Loopback0
 neighbor 10.255.37.2 soft-reconfiguration inbound
 neighbor 10.255.37.2 next-hop-self
 !
 neighbor 10.255.37.3 remote-as 65501
 neighbor 10.255.37.3 update-source Loopback0
 neighbor 10.255.37.3 soft-reconfiguration inbound
 neighbor 10.255.37.3 next-hop-self
 !
 neighbor 10.255.37.4 remote-as 65501
 neighbor 10.255.37.4 update-source Loopback0
 neighbor 10.255.37.4 soft-reconfiguration inbound
 neighbor 10.255.37.4 next-hop-self
 !
 neighbor 10.255.37.5 remote-as 65501
 neighbor 10.255.37.5 update-source Loopback0
 neighbor 10.255.37.5 soft-reconfiguration inbound
 neighbor 10.255.37.5 next-hop-self
 !
 neighbor 10.255.37.6 remote-as 65501
 neighbor 10.255.37.6 update-source Loopback0
 neighbor 10.255.37.6 soft-reconfiguration inbound
 neighbor 10.255.37.6 next-hop-self
 !
 neighbor 10.255.37.7 remote-as 65501
 neighbor 10.255.37.7 update-source Loopback0
 neighbor 10.255.37.7 soft-reconfiguration inbound
 neighbor 10.255.37.7 next-hop-self
 !
 neighbor 10.255.37.8 remote-as 65501
 neighbor 10.255.37.8 update-source Loopback0
 neighbor 10.255.37.8 soft-reconfiguration inbound
 neighbor 10.255.37.8 next-hop-self
 !
 neighbor 10.255.37.9 remote-as 65501
 neighbor 10.255.37.9 update-source Loopback0
 neighbor 10.255.37.9 soft-reconfiguration inbound
 neighbor 10.255.37.9 next-hop-self
 !
 neighbor 10.255.37.10 remote-as 65501
 neighbor 10.255.37.10 update-source Loopback0
 neighbor 10.255.37.10 soft-reconfiguration inbound
 neighbor 10.255.37.10 next-hop-self
 !
 neighbor 10.255.37.11 remote-as 65501
 neighbor 10.255.37.11 update-source Loopback0
 neighbor 10.255.37.11 soft-reconfiguration inbound
 neighbor 10.255.37.11 next-hop-self
 !
 neighbor 10.255.37.13 remote-as 65501
 neighbor 10.255.37.13 update-source Loopback0
 neighbor 10.255.37.13 soft-reconfiguration inbound
 neighbor 10.255.37.13 next-hop-self
 !
 neighbor 10.255.37.14 remote-as 65501
 neighbor 10.255.37.14 update-source Loopback0
 neighbor 10.255.37.14 soft-reconfiguration inbound
 neighbor 10.255.37.14 next-hop-self
```

---
# LR-AR4-1 
```
router bgp 65501
 bgp router-id 10.255.37.13
 bgp log-neighbor-changes
 !
 neighbor 10.255.37.1 remote-as 65501
 neighbor 10.255.37.1 update-source Loopback0
 neighbor 10.255.37.1 soft-reconfiguration inbound
 neighbor 10.255.37.1 next-hop-self
 !
 neighbor 10.255.37.2 remote-as 65501
 neighbor 10.255.37.2 update-source Loopback0
 neighbor 10.255.37.2 soft-reconfiguration inbound
 neighbor 10.255.37.2 next-hop-self
 !
 neighbor 10.255.37.3 remote-as 65501
 neighbor 10.255.37.3 update-source Loopback0
 neighbor 10.255.37.3 soft-reconfiguration inbound
 neighbor 10.255.37.3 next-hop-self
 !
 neighbor 10.255.37.4 remote-as 65501
 neighbor 10.255.37.4 update-source Loopback0
 neighbor 10.255.37.4 soft-reconfiguration inbound
 neighbor 10.255.37.4 next-hop-self
 !
 neighbor 10.255.37.5 remote-as 65501
 neighbor 10.255.37.5 update-source Loopback0
 neighbor 10.255.37.5 soft-reconfiguration inbound
 neighbor 10.255.37.5 next-hop-self
 !
 neighbor 10.255.37.6 remote-as 65501
 neighbor 10.255.37.6 update-source Loopback0
 neighbor 10.255.37.6 soft-reconfiguration inbound
 neighbor 10.255.37.6 next-hop-self
 !
 neighbor 10.255.37.7 remote-as 65501
 neighbor 10.255.37.7 update-source Loopback0
 neighbor 10.255.37.7 soft-reconfiguration inbound
 neighbor 10.255.37.7 next-hop-self
 !
 neighbor 10.255.37.8 remote-as 65501
 neighbor 10.255.37.8 update-source Loopback0
 neighbor 10.255.37.8 soft-reconfiguration inbound
 neighbor 10.255.37.8 next-hop-self
 !
 neighbor 10.255.37.9 remote-as 65501
 neighbor 10.255.37.9 update-source Loopback0
 neighbor 10.255.37.9 soft-reconfiguration inbound
 neighbor 10.255.37.9 next-hop-self
 !
 neighbor 10.255.37.10 remote-as 65501
 neighbor 10.255.37.10 update-source Loopback0
 neighbor 10.255.37.10 soft-reconfiguration inbound
 neighbor 10.255.37.10 next-hop-self
 !
 neighbor 10.255.37.11 remote-as 65501
 neighbor 10.255.37.11 update-source Loopback0
 neighbor 10.255.37.11 soft-reconfiguration inbound
 neighbor 10.255.37.11 next-hop-self
 !
 neighbor 10.255.37.12 remote-as 65501
 neighbor 10.255.37.12 update-source Loopback0
 neighbor 10.255.37.12 soft-reconfiguration inbound
 neighbor 10.255.37.12 next-hop-self
 !
 neighbor 10.255.37.14 remote-as 65501
 neighbor 10.255.37.14 update-source Loopback0
 neighbor 10.255.37.14 soft-reconfiguration inbound
 neighbor 10.255.37.14 next-hop-self
```

---
# LR-AR4-2 
```
router bgp 65501
 bgp router-id 10.255.37.14
 bgp log-neighbor-changes
 !
 neighbor 10.255.37.1 remote-as 65501
 neighbor 10.255.37.1 update-source Loopback0
 neighbor 10.255.37.1 soft-reconfiguration inbound
 neighbor 10.255.37.1 next-hop-self
 !
 neighbor 10.255.37.2 remote-as 65501
 neighbor 10.255.37.2 update-source Loopback0
 neighbor 10.255.37.2 soft-reconfiguration inbound
 neighbor 10.255.37.2 next-hop-self
 !
 neighbor 10.255.37.3 remote-as 65501
 neighbor 10.255.37.3 update-source Loopback0
 neighbor 10.255.37.3 soft-reconfiguration inbound
 neighbor 10.255.37.3 next-hop-self
 !
 neighbor 10.255.37.4 remote-as 65501
 neighbor 10.255.37.4 update-source Loopback0
 neighbor 10.255.37.4 soft-reconfiguration inbound
 neighbor 10.255.37.4 next-hop-self
 !
 neighbor 10.255.37.5 remote-as 65501
 neighbor 10.255.37.5 update-source Loopback0
 neighbor 10.255.37.5 soft-reconfiguration inbound
 neighbor 10.255.37.5 next-hop-self
 !
 neighbor 10.255.37.6 remote-as 65501
 neighbor 10.255.37.6 update-source Loopback0
 neighbor 10.255.37.6 soft-reconfiguration inbound
 neighbor 10.255.37.6 next-hop-self
 !
 neighbor 10.255.37.7 remote-as 65501
 neighbor 10.255.37.7 update-source Loopback0
 neighbor 10.255.37.7 soft-reconfiguration inbound
 neighbor 10.255.37.7 next-hop-self
 !
 neighbor 10.255.37.8 remote-as 65501
 neighbor 10.255.37.8 update-source Loopback0
 neighbor 10.255.37.8 soft-reconfiguration inbound
 neighbor 10.255.37.8 next-hop-self
 !
 neighbor 10.255.37.9 remote-as 65501
 neighbor 10.255.37.9 update-source Loopback0
 neighbor 10.255.37.9 soft-reconfiguration inbound
 neighbor 10.255.37.9 next-hop-self
 !
 neighbor 10.255.37.10 remote-as 65501
 neighbor 10.255.37.10 update-source Loopback0
 neighbor 10.255.37.10 soft-reconfiguration inbound
 neighbor 10.255.37.10 next-hop-self
 !
 neighbor 10.255.37.11 remote-as 65501
 neighbor 10.255.37.11 update-source Loopback0
 neighbor 10.255.37.11 soft-reconfiguration inbound
 neighbor 10.255.37.11 next-hop-self
 !
 neighbor 10.255.37.12 remote-as 65501
 neighbor 10.255.37.12 update-source Loopback0
 neighbor 10.255.37.12 soft-reconfiguration inbound
 neighbor 10.255.37.12 next-hop-self
 !
 neighbor 10.255.37.13 remote-as 65501
 neighbor 10.255.37.13 update-source Loopback0
 neighbor 10.255.37.13 soft-reconfiguration inbound
 neighbor 10.255.37.13 next-hop-self
```