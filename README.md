# `clsa-vpn`

See also [`clsa-vpn-credentials`](https://github.com/dycw/clsa-vpn-credentials).

```bash
if [[ "$(uname -s)" =~ Linux* ]] && ! [ -x "$(command -v curl)" ]; then
  sudo apt -y install curl
fi
curl https://raw.githubusercontent.com/dycw/connect-to-clsa-vpn/master/install | bash
```

If necessary, download the VPN client from [here](http://clsavpn.clsa.com).
