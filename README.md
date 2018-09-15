# Archlinux PKGBUILDs

This repo contains `PKGBUILD` sources for various AUR packages. Packages are updated/published using [aurpublish](https://github.com/eli-schwartz/aurpublish).

## Adding a new package

Create a new directory and add the source PKBUILD and commit changes, then run `aurpublish` to publish your changes

```
aurpublish <pkg>
```

## Updating an existing AUR package

Use aurpublish to pull the repository

```
aurpublish -p <pkg>
```

Then update the sources and publish them

```
aurpublish <pkg>
```
