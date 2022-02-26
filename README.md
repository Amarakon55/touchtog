# TouchTog – Touchpad Toggle

TouchTog is a simple program to toggle the touchpad.

## Dependencies
1. portage
1. eix or portage-Utils
    * eix is recommended because it is faster and has more details.

## (Un)Installation
### Universal
#### Installation
##### Latest Git Master (Bleeding Edge)
1. Git clone the repository.
* `$ git clone https://github.com/Amarakon55/touchtog`
2. Change working directory to *touchtog*.
* `$ cd touchtog`
3. Install TouchTog using the Makefile
* `# make install`
#### Uninstallation
##### Latest Git Master (Bleeding Edge)
1. Change working directory to *touchtog*.
* `$ cd touchtog`
2. Uninstall TouchTog using the Makefile
* `# make uninstall`

### Gentoo
#### Installation
##### Latest Git Master (Bleeding Edge)
1. Add my personal [Gentoo overlay](https://github.com/Amarakon55/amarlay) using [eselect-repository](https://packages.gentoo.org/packages/app-eselect/eselect-repository)
* `# eselect repository add amarlay git https://github.com/Amarakon55/amarlay`
2. Sync my personal [Gentoo overlay](https://github.com/Amarakon55/amarlay) using `emerge`
* `# emerge --sync amarlay`
3. Emerge the TouchTog package
* `# emerge x11-misc/touchtog` or `# emerge touchtog`
#### Uninstallation
##### Latest Git Master (Bleeding Edge)
1. Unmerge the TouchTog package
* `# emerge -c x11-misc/touchtog` or `# emerge -c touchtog`
2. (Optional) Remove my overlay
* `# eselect-repository remove -f amarlay`
3. (Optional) Sync using `emerge`
* `# emerge --sync`
