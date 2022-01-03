# node-exporter-using-ansible

Here we have setup the node-exporter using ansible and configured the service as systemd.


### Output
---
 systemctl status node_exporter.service 
 
node_exporter.service - Node Exporter
   Loaded: loaded (/etc/systemd/system/node_exporter.service; enabled; vendor preset: disabled)
   Active: active (running) since Mon 2022-01-03 18:12:56 UTC; 10s ago
 Main PID: 4517 (node_exporter)
   CGroup: /system.slice/node_exporter.service
           └─4517 /usr/local/bin/node_exporter

Jan 03 18:12:56 ip-172-31-37-109.ap-south-1.compute.internal node_exporter[4517]: ts=2022-01-03T18:12:56.581Z caller=node_exporter.go:11...zone
Jan 03 18:12:56 ip-172-31-37-109.ap-south-1.compute.internal node_exporter[4517]: ts=2022-01-03T18:12:56.581Z caller=node_exporter.go:11...time
Jan 03 18:12:56 ip-172-31-37-109.ap-south-1.compute.internal node_exporter[4517]: ts=2022-01-03T18:12:56.581Z caller=node_exporter.go:11...imex

---

![image](https://github.com/Ismailpb/node-exporter-using-ansible/blob/ab05ff19422f695b3cbc7c5a29b971e4f3f9a325/Screenshot%20from%202022-01-03%2023-53-00.png)

