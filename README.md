### Notes

- Rancher Version, 2.6.9, using rc5
- Harvester Version for v1.1.0, using 10/13/22, master-61a6124a-head


### Mapping:
Focal-Server-Rancher, dockerized, 2.6.8, 192.168.1.183 -> v1.1.0 master-head 10/13, 192.168.1.220, node: 192.168.1.122
Focal-Server-Rancher, dockerized, 2.6.9-rc5, 192.168.1.56 -> v1.1.0 master-head 10/13, 192.168.1.9, node: 192.168.1.11 
Focal-Server-Rancher, dockerized, 2.6.9-rc5, 192.168.1.40 -> v1.0.3 single node harvester 192.168.1.176, node: 192.168.1.42


### Specs Virtualized Infrastructure:
- All Rancher Nodes, 4CPU 8Gi Mem, Provisioned on Harvester, mgmt-vlan, 50Gi Disk Virtio
- All Harvester Nodes, QEMU/KVM, 200Gi Disk, 8C, 16Gi Mem
