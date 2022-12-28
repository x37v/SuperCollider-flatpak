# SuperCollider Flatpak

* [SuperCollider](https://supercollider.github.io/)
* [Flatpak](https://www.flatpak.org/)

## Build

```sh
flatpak-builder --user --install --force-clean build-dir info.x37v.SuperCollider.yml
```

## Run

scide (default):

```sh
flatpak run info.x37v.SuperCollider
```

sclang:
```sh
flatpak run --command=sclang info.x37v.SuperCollider path/to/file.sc
```

