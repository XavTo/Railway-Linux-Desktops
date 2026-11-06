# Debian and Kali Railway desktops

Private XFCE desktops for Railway with generated authentication, Firefox ESR, protected file downloads and a persistent home directory.

- [Debian 13 (Trixie)](debian/README.md)
- [Kali Linux Rolling](kali/README.md)

Each distribution has its own Dockerfile and Railway configuration. Set the service root directory to `/debian` or `/kali`, attach a volume at `/config`, leave the public-domain target port on automatic and provide a strong `PASSWORD`. The template generates a unique password on deployment.
