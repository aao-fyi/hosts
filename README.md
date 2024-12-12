# Hosts
Host lists for regex-supporting DNS applications ([AdGuard Home](https://github.com/AdguardTeam/AdGuardHome)) and browser blockers ([uBlock Origin](https://github.com/gorhill/uBlock/)).

This project has **no affiliation** with any of the services mentioned. For information regarding specified services, please refer to the respective service website.

Some hosts may no longer be owned or utilized by a service, and some may be incorrect due to human error.

## Lists
Refer to the [hosts.aao.fyi](https://hosts.aao.fyi/) website for a complete list of lists.

Each service will have the following lists. Replace `.txt` with `.sum` for a SHA-256 checksum for each file.

+ `*-block-dns.txt` DNS block list.
+ `*-block-ubo.txt` uBlock block list.
+ `*-allow-ubo.txt` uBlock allow list.

Usage of the block lists will break the corresponding services.

## Editing
Make changes to hostname lists in the `data` directory.

## Issues
Open new issues in the [Codeberg Issue Tracker](https://codeberg.org/aao-fyi/hosts/issues).

## License
Hosts is distributed under the [MIT License](https://codeberg.org/aao-fyi/hosts/src/branch/main/LICENSE).
