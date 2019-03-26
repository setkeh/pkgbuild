# CONFIGURE

To Configure the DWM Package Modify the `config.def.h` file in the root of the repo.

# Build Prep

To Prep for build delete the 

```
md5sums=('a3d97ee92215071e6399691edc0f04b0'
         '19976f26deb6c0b67f8e720ff92369dc'
         '330fe03309fde6a7865147daf5812b91')
```

section from `PKGBUILD` then run `makepkg -g -f -p PKGBUILD >> PKGBUILD`

# BUILD

`makepkg`