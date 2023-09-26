# Hosts
Host lists for regex-supporting DNS services (Blocky); and browser blockers (uBlock Origin).

## Lists
Each service will have the following lists. Replace `.txt` with `.sum` for a SHA-256 checksum for each file.

+ `*-block-dns.txt` DNS block list.
+ `*-block-ubo.txt` uBlock block list.
+ `*-allow-ubo.txt` uBlock allow list.

### Social
These lists target entire services, they are intended for use only if you don't use the service. Usage of these block-lists **will** break the corresponding service(s).

#### ByteDance
Includes ByteDance and TikTok.

+ Block DNS
  - Web: https://hosts.aao.fyi/social/bytedance-block-dns.txt
  - Git: https://codeberg.org/aao-fyi/hosts/raw/branch/main/static/social/bytedance-block-dns.txt
+ Block UBO
  - Web: https://hosts.aao.fyi/social/bytedance-block-ubo.txt
  - Git: https://codeberg.org/aao-fyi/hosts/raw/branch/main/static/social/bytedance-block-ubo.txt
+ Allow UBO
  - Web: https://hosts.aao.fyi/social/bytedance-allow-ubo.txt
  - Git: https://codeberg.org/aao-fyi/hosts/raw/branch/main/static/social/bytedance-allow-ubo.txt

#### Meta
Includes Meta, Facebook, and Instagram. May impact WhatsApp, but WhatsApp domains are not included.

+ Block DNS
  - Web: https://hosts.aao.fyi/social/meta-block-dns.txt
  - Git: https://codeberg.org/aao-fyi/hosts/raw/branch/main/static/social/meta-block-dns.txt
+ Block UBO
  - Web: https://hosts.aao.fyi/social/meta-block-ubo.txt
  - Git: https://codeberg.org/aao-fyi/hosts/raw/branch/main/static/social/meta-block-ubo.txt
+ Allow UBO
  - Web: https://hosts.aao.fyi/social/meta-allow-ubo.txt
  - Git: https://codeberg.org/aao-fyi/hosts/raw/branch/main/static/social/meta-allow-ubo.txt

#### Twitter
Includes Twitter, Periscope, and Vine.

+ Block DNS
  - Web: https://hosts.aao.fyi/social/twitter-block-dns.txt
  - Git: https://codeberg.org/aao-fyi/hosts/raw/branch/main/static/social/twitter-block-dns.txt
+ Block UBO
  - Web: https://hosts.aao.fyi/social/twitter-block-ubo.txt
  - Git: https://codeberg.org/aao-fyi/hosts/raw/branch/main/static/social/twitter-block-ubo.txt
+ Allow UBO
  - Web: https://hosts.aao.fyi/social/twitter-allow-ubo.txt
  - Git: https://codeberg.org/aao-fyi/hosts/raw/branch/main/static/social/twitter-allow-ubo.txt


## Editing
Make changes to hostname lists in the `data` directory.

## License
Hosts is distributed under the [MIT License](https://codeberg.org/aao-fyi/hosts/src/branch/main/LICENSE).

This project has **no affiliation** with the services mentioned. For information regarding specified services, please refer to the respective service(s) website.

+ ByteDance and TikTok are properties of [ByteDance Ltd](https://bytedance.com/).
+ Meta, Facebook, Instagram, and WhatsApp are properties of [Meta Platforms, Inc](https://meta.com/).
+ Twitter, Periscope, Vine, and X are properties of [X Corp](https://x.com/).
