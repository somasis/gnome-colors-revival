# gnome-colors-revival
An attempt to try and consolidate all gnome-colors icons and themes into one package.
The state of the original icon pack is in extreme unkempt.
Last updated by the original authors in 2009.

The original [GNOME Colors icon theme]
was abandoned a long time ago and there appears to be no upstream activity,
but a lot of people still use it as their theme regardless of it's age, since
it is a very well made icon theme.

Since I'm one of these people, I'm going to try to take upon myself to make a
central repository of these icons, so that there can be one place for the whole
icon theme, and icons to supplement the originals.

## Included
- Colored icon themes matching to the [shiki-colors-revival] themes and the
  [arc-colors-revival] backgrounds
  - Brave (Blue)
  - Carbonite (Dark Grey)
  - Dust (Brown/Tan)
  - Human (Orange)
  - Illustrious (Pink)
  - Noble (Purple)
  - Tribute (Light Grey)
  - Wine (Red)
  - Wise (Green)

## Downloading
Either use `git` to clone this repository:
  
    git clone https://github.com/Somasis/gnome-colors-revival
  
or just [download the latest release](releases).

## Installing
1. Open a terminal in this repo's directory.
2. `make`
3. `make install` or `make user-install`

Use `make help` if you want to know what else the Makefile can do.

**Exherbo users**: There is an exheres in ::somasis; x11-themes/gnome-colors-revival.

## Credits
- Skype icons were created by [MastroPino].
- Dropbox tray icons were created by [mechanical].
- Filezilla icons were created by [DarKobra].
- HexChat icons are based off of [HexChat's original icons]
- The original icon theme was created by [perfectska04] and [trollixx].
  - The authors have since disappeared from the face of the earth.
- All is licensed under GPLv2, and so is this repo.

[GNOME Colors icon theme]: http://code.google.com/p/gnome-colors/
[MastroPino]: http://mastropino.deviantart.com/art/eSkype-204048506
[mechanical]: http://gnome-look.org/content/show.php/Dropbox+Color+Status+Icons?content=132827
[DarKobra]: http://darkobra.deviantart.com/art/FileZilla-Tango-Icon-103292389
[HexChat's original icons]: https://github.com/hexchat/hexchat/blob/master/data/icons/hexchat.svg
[perfectska04]: https://code.google.com/u/perfectska04
[trollixx]: https://code.google.com/u/trollixx
[releases]: https://github.com/Somasis/gnome-colors-revival/releases
[arc-colors-revival]: https://github.com/Somasis/arc-colors-revival
[shiki-colors-revival]: https://github.com/Somasis/shiki-colors-revival