# PKGCL -- Get changelogs for Arch Linux packages

## Install
I've put this on the [AUR](https://aur.archlinux.org/packages.php?ID=56183)

Or just, you know, download the script and put it wherever you like.

Depends on [nokogiri](http://rubygems.org/gems/nokogiri).

## Usage
See `pkgcl -h`

It also takes newline delimited stdin, so I like doing this:
`sudo pacman -Sy; pacman -Qqu | pkgcl`.

## Tested versions
I've tested this with `ruby 1.9.3p0 (2011-10-30 revision 33570)`
and `nokogiri (1.5.0)`.

## Note
This is my first ruby script that does anything useful, so I may have made grave
errors. Any and all suggestions are welcome!

## License
Licensed under the [WTFPL](http://sam.zoy.org/wtfpl/)
