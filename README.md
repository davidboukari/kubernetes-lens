# kubernetes-lens

* https://snapcraft.io/install/kontena-lens/centos
* https://sleeplessbeastie.eu/2020/06/24/how-to-install-lens-the-kubernetes-ide/

## Install lens
```
sudo yum install epel-release
sudo yum install snapd
sudo systemctl enable --now snapd.socket
sudo ln -s /var/lib/snapd/snap /snap
```

## Lanch lens => kontena-lens
```
sudo snap install kontena-lens --classic
```
