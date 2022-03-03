![demo](./demo.gif)

# Firewall GeoIP script for firewalld

For those who need to block unwanted IPv4 and IPv6 target ranges by countries at server level using firewalld. I, myself have some use cases where servers are front facing the Internet, without WAF or CDN, so I wanted to easily secure them using firewalld. 

## Usage

- [ ] Clone this repo
- [ ] Define the countries ISO Alpha-2 code you want to block at line 18 (ZONES). [Reference](https://www.ipdeny.com/ipblocks/)
- [ ] Execute `bash firewalld`
- [ ] Define a @weekly cronjob 

## Supported Operating Systems

- [ ] Debian/Ubuntu
- [ ] RHEL/CentOS

## Contribute

All suggestions, feedback, or bug reports are welcome. Feel free to submit a PR. 

## Disclaimer

Use this script at your own risk! The author assumes no responsibility for any damages of any kind. It is strongly recommended you test this out on a test server before implemeting on production servers.