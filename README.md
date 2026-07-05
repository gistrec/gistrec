## Aleksandr Kovalko

Backend & cloud engineer — C++, Python, Linux. 8+ years building backend systems.

I build backend services and low-level tools, keep my infrastructure as code,
and occasionally wear the DevOps / SRE hat.

### Systems & tools

- [filecast](https://github.com/gistrec/filecast) — file transfer over LAN via UDP broadcast
  with packet-loss recovery (C++, Linux/macOS/Windows). Installable via
  [Homebrew](https://github.com/gistrec/homebrew-filecast).
- [geo-utils-cpp](https://github.com/gistrec/geo-utils-cpp) — header-only C++17 library
  for lat/lng geometry: distance, bearing, area, point-in-polygon. Packaged for
  [vcpkg](https://github.com/microsoft/vcpkg/tree/master/ports/geo-utils-cpp) and
  [xmake](https://github.com/xmake-io/xmake-repo/tree/master/packages/g/geo-utils-cpp).
- [C-P2P-Chat](https://github.com/gistrec/C-P2P-Chat) — decentralized P2P chat in pure C:
  UDP, non-blocking I/O, peer auto-discovery, ncurses TUI.
- [RakLib-Proxy](https://github.com/gistrec/RakLib-Proxy) — proxying UDP packets
  inside a Linux kernel module.

### Infrastructure & security

- [gistrec-cloud/infra](https://github.com/gistrec-cloud/infra) — my server fleet as code:
  Ansible (SSH hardening, nftables + fail2ban, nginx, netdata) and Terraform
  (Cloudflare DNS, AWS, Yandex Cloud).
- [nginx-scanner-trap](https://github.com/gistrec/nginx-scanner-trap) — turns an nginx box
  into a honeypot: the first probe of `/.env` or `/.git` gets the scanner banned
  on all ports via fail2ban + nftables.

### Toolbox

C++17 · C · Python · Bash · Linux · nginx · nftables / fail2ban · Ansible · Terraform · Docker · AWS · ClickHouse
