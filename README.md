# ArchLinux pkgbuilds

A repo of various software packages that I maintain as part of the [ArchLinux User Repository](https://aur.archlinux.org/)

# Compiling Steps

All packages should run within a clean environment. To do this, we use ArchLinux standard

  * run [extra-x86_64-build](https://wiki.archlinux.org/title/DeveloperWiki:Building_in_a_clean_chroot)
  * Run `namcap` on `PKGBUILD`
  * Run `namcap` on `PKGBUILD.pkg.tar.zst`
  * Test!

# Publish Steps

Use [aurpublish](https://github.com/eli-schwartz/aurpublish)

  * Make changes
  * Commit using `git commit -s`
  * Run `aurpublish PACKAGE`
