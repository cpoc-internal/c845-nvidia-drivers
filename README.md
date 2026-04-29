# c845-nvidia-drivers

1.Clone the repository in your Ubuntu server
```
git clone https://github.com/cpoc-internal/c845-nvidia-drivers.git
```

Cuda-13.0
```
chmod +x /root/c845-nvidia-drivers/cuda-13.0.sh
sudo -u root /root/c845-nvidia-drivers/cuda-13.0.sh
```
configure nics non persistance
server 1
```
chmod +x /root/c845-nvidia-drivers/server-1-non-persistant.sh
sudo -u root /root/c845-nvidia-drivers/server-1-non-persistant.sh
```
server 2
```
chmod +x /root/c845-nvidia-drivers/server-2-non-persistant.sh
sudo -u root /root/c845-nvidia-drivers/server-2-non-persistant.sh
```
