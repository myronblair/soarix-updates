# Soarix updates

Public update channel for [Soarix](https://getsoarix.com). This repository contains **only**
small channel files that tell a Soarix computer which version is current and what changed.
It holds no operating-system files and no source code.

- `stable.json` - tested releases (the default channel)
- `testing.json` - early releases
- `cosign.pub` - public key used to verify signed Soarix images

The operating system image itself is not published here. It is delivered to licensed computers by the
Soarix license server (`licensing.tomtomenterprises.com`). A Soarix computer checks these files with
`soarix-update status`.

Copyright (c) TomTom Enterprises. Soarix is based on Fedora; Fedora is a trademark of Red Hat, Inc.
