# flatpak-repo

Repository for Flatpak (not all the stuff here are multiarch)

Command to add .flatpak (only for repository maintainers):

```bash
$ flatpak build-import-bundle repo <flatpak file>
```

Command to add this repo:

```bash
$ flatpak remote-add --user --no-gpg-verify lebao3105 https://lebao3105.github.io/flatpak-repo/repo.flatpak
```

To list all packages from this repo:

```bash
$ flatpak remote-ls | grep lebao3105
```
