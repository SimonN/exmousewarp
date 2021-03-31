D/Allegro 5 Mouse Warping
=========================

Conversion to D of the Allegro 5 example that tests `al_mouse_set_xy()`.

Build instructions
------------------

1. Install a D toolchain.
    * On Arch: `# pacman -S dlang`
    * On Debian/Ubuntu: `# apt-get install ldc dub`
    * On macOS, install [Homebrew](https://brew.sh/), then run `$ brew install ldc dub`.

2. Install Allegro 5.2.
    * On Arch: `# pacman -S pkgconf allegro`
    * On Debian/Ubuntu: `# apt-get install pkgconf liballegro5-dev`, this will not install any addons for audio, text, ..., those aren't needed for this minimal example.
    * On macOS: `brew install allegro`

3. Clone this _exmousewarp_ repository, enter its main directory, run `dub`.
