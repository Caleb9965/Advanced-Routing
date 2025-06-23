# Edge
```
en
conf t
hostname RTR-Edge
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
!
Router OSPF 37
!
interface G0/0
description To_SW1
ip address 10.37.1.1 255.255.255.248
ip ospf 37 area 0
no shutdown
!
interface G0/1
description To_BB-RTR-1-G01
ip address 10.37.1.9 255.255.255.252
ip ospf 37 area 0
no shutdown
!
interface G0/2
description To_BB-RTR-2-G01
ip address 10.37.1.30 255.255.255.252
ip ospf 37 area 0
no shutdown
!
interface G0/3
description To_Cloud
ip address dhcp
no shutdown
!
Interface Loop0
ip address 10.255.37.1 255.255.255.255
ip ospf 37 area 0
no shut
```
# BB-RTR-1
```
en
conf t
hostname BB-RTR-1
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
area 0 range 10.37.1.0 255.255.255.192
area 1 range 10.37.1.64 255.255.255.224
!
interface G0/0
description To_SW1
ip address 10.37.1.2 255.255.255.248
ip ospf 37 area 0
no shut
!
interface G0/1
description To_Edge-RTR-G01
ip address 10.37.1.10 255.255.255.252
ip ospf 37 area 0
no shut
!
interface G0/2
description To_BB-RTR-4-G02
ip address 10.37.1.13 255.255.255.252
ip ospf 37 area 0
no shut
!
interface G0/3 
description To_LR-AR1-1-G01
ip address 10.37.1.65 255.255.255.252
ip ospf 37 area 1
no shut
!
interface G0/4
description To_LR-AR1-2-G00
ip address 10.37.1.69 255.255.255.252
ip ospf 37 area 1
no shut
!
interface Loop0
ip address 10.255.37.2 255.255.255.255
ip ospf 37 area 0
no shut
!
```
# BB-RTR-4
```
en
conf t
hostname BB-RTR-4
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
Conf t
Router ospf 37
area 0 range 10.37.1.0 255.255.255.192
area 1 range 10.37.1.64 255.255.255.224
area 2 range 10.37.1.96 255.255.255.224
!
interface G0/0
description To_SW1
ip address 10.37.1.5 255.255.255.248
ip ospf 37 area 0
no shut
!
interface G0/1 
description To_BB-RTR-5-G01
ip address 10.37.1.17 255.255.255.252
ip ospf 37 area 0
no shut
!
interface G0/2
description To_BB-RTR-1-G02
ip address 10.37.1.14 255.255.255.252
ip ospf 37 area 0
no shut
!
interface G0/3
description To_LR-AR1-2-G01
ip address 10.37.1.77 255.255.255.252
ip ospf 37 area 1
no shut
!
interface G0/4
description To-LR-AR1-1-G00
ip address 10.37.1.73 255.255.255.252
ip ospf 37 area 1
no shut
!
interface G0/5 
description To_LR-AR2-1-G01
ip address 10.37.1.97 255.255.255.252
ip ospf 37 area 2
no shut
!
interface G0/6 
description To_LR-AR2-2-G00
ip address 10.37.1.101 255.255.255.252
ip ospf 37 area 2
no shut
!
interface Loop0
ip address 10.255.37.5 255.255.255.255
ip ospf 37 area 0
no shut
!
```
# BB-RTR-5
```
en
conf t
hostname BB-RTR-5
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
area 0 range 10.37.1.0 255.255.255.192
area 2 range 10.37.1.96 255.255.255.224
area 3 range 10.37.1.128 255.255.255.224
!
interface G0/0
description To_SW1
ip address 10.37.1.6 255.255.255.248
ip ospf 37 area 0
no shut
!
interface G0/1
description To_BB-RTR-4-G01
ip address 10.37.1.18 255.255.255.252
ip ospf 37 area 0
no shut
!
interface G0/2
description To_BB-RTR-3-G01
ip address 10.37.1.21 255.255.255.252
ip ospf 37 area 0
no shut
!
interface G0/3
description To_LR-AR2-1-G00
ip address 10.37.1.105 255.255.255.252
ip ospf 37 area 2
no shut
!
interface G0/4
description To_LR-AR3-2-G00
ip address 10.37.1.129 255.255.255.252
ip ospf 37 area 3
no shut
!
interface G0/5
description To_LR-AR2-2-G01
ip address 10.37.1.109 255.255.255.252
ip ospf 37 area 2
no shut
!
interface G0/6 
description To_LR-AR3-1-G01
ip address 10.37.1.133 255.255.255.252
ip ospf 37 area 3
no shut
!
interface Loop0
ip address 10.255.37.5 255.255.255.255
ip ospf 37 area 0
no shut
!
```
# BB-RTR-3
```
en
conf t
hostname BB-RTR-3
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
area 0 range 10.37.1.0 255.255.255.192
area 3 range 10.37.1.128 255.255.255.224
area 4 range 10.37.1.160 255.255.255.224
!
interface G0/0
description To_SW1
ip address 10.37.1.4 255.255.255.248
ip ospf 37 area 0
no shut
!
interface G0/1
description To_BB-RTR-5-G02
ip address 10.37.1.22 255.255.255.252
ip ospf 37 area 0
no shut
!
interface G0/2 
description To_BB-RTR-2-G02
ip address 10.37.1.25 255.255.255.252
ip ospf 37 area 0
no shut
!
interface G0/3
description To_LR-AR4-1-G01
ip address 10.37.1.161 255.255.255.252
ip ospf 37 area 4
no shut
!
interface G0/4
description To_LR-AR4-2-G00
ip address 10.37.1.165 255.255.255.252
ip ospf 37 area 4
no shut
!
interface G0/5 
description To_LR-AR3-1-G00
ip address 10.37.1.137 255.255.255.252
ip ospf 37 area 3
no shut
!
interface G0/6
description To_LR-AR3-2-G01
ip address 10.37.1.141 255.255.255.252
ip ospf 37 area 3
no shut
!
interface Loop0
ip address 10.255.37.5 255.255.255.255
ip ospf 37 area 0
no shut
!
```
# BB-RTR-2
```
en
conf t
hostname BB-RTR-2
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
area 0 range 10.37.1.0 255.255.255.192
area 4 range 10.37.1.160 255.255.255.224
!
interface G0/0
description To_SW1
ip address 10.37.1.3 255.255.255.248
ip ospf 37 area 0
no shut
!
interface G0/1
description To_Edge-RTR-G02
ip address 10.37.1.29 255.255.255.252
ip ospf 37 area 0
no shut
!
interface G0/2 
description To_BB-RTR-3-G02
ip address 10.37.1.26 255.255.255.252
ip ospf 37 area 0
no shut
!
interface G0/3
description To_LR-AR4-2-G01
ip address 10.37.1.169 255.255.255.252
ip ospf 37 area 4
no shut
!
interface G0/4
description To_LR-AR4-1-G00
ip address 10.37.1.173 255.255.255.252
ip ospf 37 area 4
no shut
!
interface Loop0
ip address 10.255.37.5 255.255.255.255
ip ospf 37 area 0
no shut
!
```