# `clsa-vpn`

See also [`clsa-vpn-credentials`](https://github.com/dycw/clsa-vpn-credentials).

```bash
if ! [ -x "$(command -v curl)" ]; then
  sudo apt -y install curl
fi
URL=https://raw.githubusercontent.com/dycw/connect-to-clsa-vpn/master/install
curl "$URL" | bash
```

If necessary, download the VPN client from [here](http://clsavpn.clsa.com).
