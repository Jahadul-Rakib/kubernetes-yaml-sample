#To Perform statefulset sometimes need more Resource. If Required, Then-

* **minikube stop**
* **minikube delete**
* **Edit the /etc/default/grub file. Add or edit the GRUB_CMDLINE_LINUX line to add the following two key-value pairs:
GRUB_CMDLINE_LINUX="cgroup_enable=memory swapaccount=1"**
* **minikube start --memory 5120 --cpus=4**
* ##### **_Stateful works direct storage-class without PVC._**