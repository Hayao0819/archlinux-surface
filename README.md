# ArchLinux for Surface

## How to build

### Import keys

```bash
curl -s https://raw.githubusercontent.com/linux-surface/linux-surface/master/pkg/keys/surface.asc | sudo pacman-key --add -
sudo pacman-key --lsign-key 56C464BAAC421453
```

### Install archiso

```bash
sudo pacman -S archiso
```

### Start build

```bash
sudo mkarchiso -v .
```
