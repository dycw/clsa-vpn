# `connect-to-github`

Connect a new machine to the CLSA VPN

```bash
if ! [ -x "$(command -v curl)" ]; then
  sudo apt -y install curl
fi
curl https://raw.githubusercontent.com/dycw/connect-to-clsa-vpn/master/install | bash
```
