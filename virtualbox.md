# Virtual Box
### Commands when managing headless VM
* To get the list of installed VMs
```
VBoxManage list vms
"minikube" {900f481d-98fc-4e06-b3ea-62a95c6efbb0}
```
* To properties of the VM like the IPs
```
VBoxManage guestproperty enumerate minikube
```
or for a particular pattern
```
VBoxManage guestproperty enumerate minikube "/VirtualBox/GuestInfo/Net/0/V4/IP"
```
