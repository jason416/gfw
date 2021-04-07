# gfw
generate pac file for gfw

## packages

```
sudo apt install python3-pip
sudo pip3 install genpac
sudo apt install shadowsocks-libev
sudo cp /etc/shadowsocks-libev/config.json /etc/shadowsocks/client.json
# modify client connection args
sudo systemctl enable shadowsocks-libev-local@client.service # @<file> must be the same as <file>.json
sudo systemctl start shadowsocks-libev-local@lee.service
```
