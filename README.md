# Hosts
Host lists for common services in adblock and regex syntax. Useful with ([AdGuard Home](https://github.com/AdguardTeam/AdGuardHome)) and ([uBlock Origin](https://github.com/gorhill/uBlock/)).

This project has **no affiliation** with any of the services mentioned. For information regarding specified services, please refer to the respective service website.

Some hosts may no longer be owned or utilized by a service, and some may be incorrect due to human error.

## Lists
Refer to the [hosts.aao.fyi](https://hosts.aao.fyi/) website for a complete list of lists.

Each service will have the following lists. Replace `.txt` with `.sum` for a SHA-256 checksum for each file.

+ `*-block-rgx.txt` Regex syntax block list.
+ `*-block-adb.txt` Adblock syntax block list.
+ `*-allow-adb.txt` Adblock syntax allow list.

Usage of the block lists will break the corresponding services.

## Editing
Make changes to hostname lists in the `data` directory.

## Issues
Open new issues in the [Codeberg Issue Tracker](https://codeberg.org/aao-fyi/hosts/issues).

## License
Hosts is distributed under the [MIT License](https://codeberg.org/aao-fyi/hosts/src/branch/main/LICENSE).
