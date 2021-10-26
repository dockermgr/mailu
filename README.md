# Welcome to dockermgr mailu installer 👋
  
## mailu README  
  
### Requires scripts to be installed

```shell
 sudo bash -c "$(curl -LSs <https://github.com/dockermgr/installer/raw/main/install.sh>)"
 dockermgr --config && dockermgr install scripts  
```

#### Automatic install/update  

```shell
dockermgr install mailu
```


#### Manual install

```shell
git clone https://github.com/dockermgr/mailu "$HOME/.local/share/CasjaysDev/dockermgr/mailu"
bash -c "$HOME/.local/share/CasjaysDev/dockermgr/mailu/install.sh"
```
  
#### Just run

```shell
mkdir -p "$HOME/.local/share/srv/docker/mailu/"
git clone <https://github.com/dockermgr/mailu> "$HOME/.local/share/CasjaysDev/dockermgr/mailu"
cd "$HOME/.local/share/CasjaysDev/dockermgr/mailu" && sudo docker-compose -p mailu up -d 
```

## Author  

👤 **Jason Hempstead**  
