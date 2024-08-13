# Wireguard
WireGuard installer for Ubuntu, Debian, AlmaLinux, Rocky Linux, CentOS and Fedora.

### Installation

The virtual machine (EC2, Azure VM, Huawei ECS) need to just have a private IP with only one network interface.
Elastic IP will be the Public IP gateway of the VM.

`Internet  ---> Elastic IP ---> Private Interface of VM`

Run the script and follow the assistant:

`wget https://raw.githubusercontent.com/mehmetihsansevinc/wireguard/main/wireguard-server.sh -O wireguard-install.sh && bash wireguard-install.sh`

You can run it to add more users, remove some of them or uninstall WireGuard.
