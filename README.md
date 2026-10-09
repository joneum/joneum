# Jochen Neumeister

FreeBSD ports committer from Solingen, Germany. I look after nginx, MySQL and
FreeIPA on FreeBSD, and when a port needs something that does not exist yet,
I build it.

Blog and write-ups: **[blog.bsdproject.de](https://blog.bsdproject.de)**

## nginx modules

My nginx modules live in the
**[sysadmin-labs](https://github.com/sysadmin-labs)** organization:

| Module | What it does |
|---|---|
| [nginx-form-input-module](https://github.com/sysadmin-labs/nginx-form-input-module) | Parses `application/x-www-form-urlencoded` request bodies into nginx variables |
| [nginx-let-module](https://github.com/sysadmin-labs/nginx-let-module) | Evaluates an arithmetic or string expression into a variable |
| [nginx-zstd-module](https://github.com/sysadmin-labs/nginx-zstd-module) | Zstandard output filter plus a server for precompressed `.zst` files |
| [nginx-slowfs-cache-module](https://github.com/sysadmin-labs/nginx-slowfs-cache-module) | Caches files from a slow filesystem onto a fast one |

The last three are forks of upstream projects that had gone quiet. The fixes
stay there until upstream wants them back.

## FreeBSD ports

Ports I maintain include:

- `www/immich`: the self-hosted photo and video library, with its machine
  learning side
- `net/freeipa-server`: the FreeIPA server on FreeBSD, with
  [documentation of what works and what differs from Linux](https://github.com/joneum/FreeBSD-freeipa-server)
- `www/nginx`, `www/nginx-devel`, `www/freenginx`
- `databases/mysql*`

Fixes go upstream or into the ports tree, never only into a private fork.

## Distfile hosting

Some ports ship artifacts that the ports framework cannot build offline.
Those live here so the ports stay reproducible:

- [FreeBSD-CodeServer](https://github.com/joneum/FreeBSD-CodeServer)
- [FreeBSD-Semaphore](https://github.com/joneum/FreeBSD-Semaphore): prebuilt Vue web UI for `net-mgmt/semaphore`
- [FreeBSD-Immich](https://github.com/joneum/FreeBSD-Immich): distfiles for `www/immich`

## Contact

Bug reports for a port: the FreeBSD [Bugzilla](https://bugs.freebsd.org/).
Everything else: issues on the repository in question.

## License

BSD 2-Clause, see [LICENSE](LICENSE).
