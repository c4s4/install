# Install Script

This script should live in server directory with binaries for various OS and architectures, with names such as `foo-linux-amd64`. Possible OS and architecture combinations for Golang are listed with `go tool dist list`.

To install a binary for target OS and architecture, one should run `sh -c "$(curl https://sweetohm.net/dist/neon/install)"` where *https://sweetohm.net/dist* is the root directory for appliations, *neon* is given application.

To customize this script you must set `NAME` and `DIST_URL` with the name of the software and the root directory for softwares on the server.
