# k8shomemade

## Fix erreur avec docker sur raspberry
sudo apt-get update; sudo apt-get install --reinstall raspberrypi-bootloader raspberrypi-kernel

## Installer un raspberry :
activer le ssh
    ssh-copy-id -i ~/.ssh/id_rsa pi@192.168.1.23
    
## Pb docker sur master avec centos 8 :
    https://vexpose.blog/2020/04/02/installation-of-docker-fails-on-centos-8-with-error-package-containerd-io-1-2-10-3-2-el7-x86-64-is-excluded/