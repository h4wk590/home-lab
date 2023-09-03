# Home Lab

Current-ish state of the lab:

![](/img/home-lab-network-v1.jpg)

A space to create, learn, and share
Includes some boiler platers and live configs.

- Keeping this as a public repo also helps utilize secure coding principles
- SSH keypairs, env files, and the like
- View `img` directory to see some of the deployed service images

I choose to keep all my home services within my local network besides Nextcloud (which I use Cloudflare's HTTPS Tunnel). I use [PIPVN](https://www.pivpn.io/) to access my home lab remotely. I utilize Ubiquiti Unifi gateway to secure my networks behind firewalls and static routing (IoT network doesn't access the internet directly, etc).

Any service that I do want to have external access to is hosted from my VPS Instance in DigitalOcean.

## Currently Working On...

- [x] 3 Node K3s cluster 
- [x] Longhorn persistent storage 
- [x] Letsencrypt HTTPS certificates on services 
- [x] Uptime Kuma monitoring  
- [x] Finally putting Unifi controller into a container where it belongs
- [x] Nextcloud instance
- [x] Cloudflare HTTPS tunnel
- Homer Dashboard
