# LR-AR1-1
```
en
conf t
hostname LR-AR1-1
enable secret cisco
username cisco secret cisco
line con 0
logging synch
login local
line vty 0 4 
logging synch
login local
end
wr mem
!
conf t
router ospf 37
!
interface G0/0
description To-BB-RTR-4-G04
ip address 10.37.1.74 255.255.255.252
ip ospf 37 area 1
no shut
!
interface G0/1
description To-BB-RTR-1-G03
ip address 10.37.1.66 255.255.255.252
ip ospf 37 area 1
no shut
!
interface G0/2 
description To-LR-AR1-2-G02
ip address 10.37.1.81 255.255.255.252
ip ospf 37 area 1
no shut
!
interface Loop0 
ip address 10.255.37.7 255.255.255.255
ip ospf 37 area 1
no shut
!
end
wr mem
```
# LR-AR1-2
```
en
conf t
hostname LR-AR1-2
enable secret cisco
username cisco secret cisco
line con 0
logging synch
login local
line vty 0 4 
logging synch
login local
end
wr mem
!
conf t
router ospf 37
!
interface G0/0
description To-BB-RTR-1
ip address 10.37.1.70 255.255.255.252
ip ospf 37 area 1
no shut
!
interface G0/1 
description To-BB-RTR-4
ip address 10.37.1.78 255.255.255.252
ip ospf 37 area 1
no shut
!
interface G0/2
description To-LR-AR1-1
ip address 10.37.1.82 255.255.255.252
ip ospf 37 area 1
no shut
!
interface Loop0 
ip address 10.255.37.8 255.255.255.255
ip ospf 37 area 1
no shut
!
```
# LR-AR2-1
```
en
conf t
hostname LR-AR2-1
enable secret cisco
username cisco secret cisco
line con 0
logging synch
login local
line vty 0 4 
logging synch
login local
end
wr mem
!
conf t
router ospf 37
!
interface G0/0
description To_BB-RTR-5-G03
ip address 10.37.1.106 255.255.255.252
ip ospf 37 area 2
no shut
!
interface G0/1 
description To_BB-RTR-4-G05
ip address 10.37.1.98 255.255.255.252
ip ospf 37 area 2
no shut
!
interface G0/2
description To_LR-AR2-2-G02
ip address 10.37.1.113 255.255.255.252
ip ospf 37 area 2
no shut
!
interface Loop0
ip address 10.255.37.9
ip ospf 37 area 2
no shut
!
```
# LR-AR2-2
```
en
conf t
hostname LR-AR2-2
enable secret cisco
username cisco secret cisco
line con 0
logging synch
login local
line vty 0 4 
logging synch
login local
end
wr mem
!
conf t
router ospf 37
!
interface G0/0 
description To_BB-RTR-4-G06
ip address 10.37.1.102 255.255.255.252
ip ospf 37 area 2
no shut
!
interface G0/1 
description To_BB-RTR-5-G05
ip address 10.37.1.110 255.255.255.252
ip ospf 37 area 2
no shut
!
interface G0/2
description To_LR-AR2-2-G02
ip address 10.37.1.114 255.255.255.252
ip ospf 37 area 2
no shut
!
interface Loop0
ip address 10.255.37.10 255.255.255.255
ip ospf 37 area 2
no shut
!
end
wr mem
sh ip ospf neighbor
```
# LR-AR3-1
```
en
conf t
hostname LR-AR3-1
enable secret cisco
username cisco secret cisco
line con 0
logging synch
login local
line vty 0 4 
logging synch
login local
end
wr mem
!
conf t
interface Loop0
ip address 10.255.37.11 255.255.255.255
ip ospf 37 area 3
no shut
!
router ospf 37
!
interface G0/0 
description To_BB-RTR-3-G05
ip address 10.37.1.138 255.255.255.252
ip ospf 37 area 3
no shut
!
interface G0/1 
description To_BB-RTR-5-G06
ip address 10.37.1.134 255.255.255.252
ip ospf 37 area 3
no shut
!
interface G0/2
description To_LR-AR3-2-G02
ip address 10.37.1.145 255.255.255.252
ip ospf 37 area 3
no shut
!
end
wr mem
sh ip ospf neighbor
```
# LR-AR3-2
```
en
conf t
hostname LR-AR3-2
enable secret cisco
username cisco secret cisco
line con 0
logging synch
login local
line vty 0 4 
logging synch
login local
end
wr mem
!
conf t
router ospf 37
!
interface G0/0 
description To_BB-RTR-5-G04
ip address 10.37.1.130 255.255.255.252
ip ospf 37 area 3
no shut
!
interface G0/1 
description To_BB-RTR-3-G06
ip address 10.37.1.142 255.255.255.252 
ip ospf 37 area 3
no shut
!
interface G0/2 
description To_LR-AR3-1-G02
ip address 10.37.1.146 255.255.255.252 
ip ospf 37 area 3
no shut
!
interface Loop0
ip address 10.255.37.12 255.255.255.255
ip ospf 37 area 3
no shut
!
end 
wr mem
```
# LR-AR4-1
```
en
conf t
hostname LR-AR4-1
enable secret cisco
username cisco secret cisco
line con 0
logging synch
login local
line vty 0 4 
logging synch
login local
end
wr mem
!
conf t
router ospf 37
!
interface G0/0
description To_BB-RTR-2-G04
ip address 10.37.1.174 255.255.255.252 
ip ospf 37 area 4
no shut
!
interface G0/1 
description To_BB-RTR-3-G03
ip address 10.37.1.162 255.255.255.252 
ip ospf 37 area 4
no shut
!
interface G0/2
description To_LR-AR4-2-G02
ip address 10.37.1.177 255.255.255.252 
ip ospf 37 area 4
no shut
!
interface Loop0
ip address 10.255.37.13 255.255.255.255
ip ospf 37 area 4
no shut
!
end
wr mem
!
```
# LR-AR4-2
```
en
conf t
hostname LR-AR4-2
enable secret cisco
username cisco secret cisco
line con 0
logging synch
login local
line vty 0 4 
logging synch
login local
end
wr mem
!
conf t
router ospf 37
!
interface G0/0
description To_BB-RTR-3-G04
ip address 10.37.1.166 255.255.255.252 
ip ospf 37 area 4
no shut
!
interface G0/1
description To_BB-RTR-2-G03
ip address 10.37.1.170 255.255.255.252 
ip ospf 37 area 4
no shut
!
interface G0/2
description To_LR-AR4-1-G02
ip address 10.37.1.178 255.255.255.252 
ip ospf 37 area 4
no shut
!
interface Loop0
ip address 10.255.37.14 255.255.255.255
ip ospf 37 area 4
no shut
!
end
wr mem
!
```