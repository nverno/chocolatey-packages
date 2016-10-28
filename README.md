# Chocolatey Packages

[![build](https://ci.appveyor.com/api/projects/status/github/nverno/chocolatey-packages?svg=true)](https://ci.appveyor.com/project/nverno/chocolatey-packages)
[Update status](https://gist.github.com/nverno/YOUR_GIST_ID)

---

## Chocolatey Packages


### Folder Structure

* au - The scripts for running Automatic Updater (AU) are here.
* automatic - where automatic packaging and packages are kept. These are packages that are automatically maintained using either [AU](https://chocolatey.org/packages/au) or [Ketarin](https://chocolatey.org/packages/ketarin)/[ChocolateyPackageUpdater](https://chocolatey.org/packages/chocolateypackageupdater) combo.
* icons - Where you keep icon files for the packages. This is done to reduce issues when packages themselves move around.
* ketarin - where ketarin jobs (aka applications or searches) exported as XML are kept. This is done to allow ease of contribution.
* manual - where packages that are not automatic are kept.
* ops - scripts, jobs, and other items for ensuring automatic packaging.
* setup - items for prepping the system to ensure for auto packaging.

For setting up your own automatic package repository, please see [Automatic Packaging](https://chocolatey.org/docs/automatic-packages)

### Requirements

* Chocolatey (choco.exe)

#### AU

* PowerShell v4+.
* The [AU module](https://chocolatey.org/packages/au).
