# Fivem-Proxy-Install.sh
Handy script to install nginx as a proxy for your FiveM/RedM server.


## Requirements
- Debian linux distribution (Tested on debian 10/11)
- Root access
- A domain name
- A FiveM/RedM server

## Installation
1. Download the script
2. Make it executable: `chmod +x fivem-proxy-install.sh`
3. Run it: `./fivem-proxy-install.sh`

## Usage
1. Follow the instructions
2. Enjoy your new proxy!

## Credits
- [Nginx](https://nginx.org/)
- [Certbot](https://certbot.eff.org/)
- [Let's Encrypt](https://letsencrypt.org/)
- [FiveM](https://fivem.net/)
- [RedM](https://redm.gg/)
- [Script creator](https://github.com/MathiAs2Pique)

## Additional notes
- I personnaly recommend to use CloudFlare: DNS, Proxy and Edge Cache are really useful.
- Please do not use the built-in nginx cache, as it's a mess if you want to udpate your scripts, and it would cost you a lot more than CloudFlare.
- If you have your own SSL certificate, then just check web.conf to edit what needs to be edited.
- If you want to use a custom port, then just check web.conf to edit what needs to be edited.
- A **single** proxy is **not useful at all** as a DDoS protection, but it can be useful to hide your IP address.
