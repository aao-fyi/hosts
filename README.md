# Hosts
Host lists to be used with DNS services that support regex (PiHole) and browser blocker (uBlock Origin).

## Lists
Hosts lists for various services. There are different files for each application, select accordingly. Each service will have the following lists. Replace `.txt` with `.sum` for a SHA-256 checksum for each file.

+ `service-block-dns.txt` DNS block list, zero IP.
+ `service-block-ubo.txt` uBlock block list.
+ `service-allow-ubo.txt` uBlock allow list.

### Social
These lists target entire services, they are intended for use only if you don't use the service. Usage of these block-lists **will** break the corresponding service(s).

+ Meta
  - Blocks Meta, Facebook, and Instagram.
  - May impact WhatsApp, but WhatsApp domains are not included.
+ TikTok
  - Blocks TikTok and ByteDance.
+ Twitter
  - Blocks Twitter and Periscope.

## Contributing
Make changes to hostname lists in the `data` directory.
