# How-to-use-IOTstack

- REF : https://github.com/SensorsIot/IOTstack
- or  : https://sensorsiot.github.io/IOTstack/Basic_setup/

## automatic (recommended)
```
sudo apt install -y curl
curl -fsSL https://raw.githubusercontent.com/SensorsIot/IOTstack/master/install.sh | bash
cd ~/IOTstack
./menu.sh
```

## manual
```
sudo apt install -y git
git clone https://github.com/SensorsIot/IOTstack.git ~/IOTstack
cd ~/IOTstack
./menu.sh
```

## start docker
```
cd ~/IOTstack
docker-compose up -d
```
