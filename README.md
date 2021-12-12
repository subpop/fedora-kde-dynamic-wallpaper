# fedora-kde-dynamic-wallpaper

This is the Fedora 35 wallpaper, converted to a
[plasma5-wallpapers-dynamic](https://github.com/zzag/plasma5-wallpapers-dynamic)
compatible file (HEIC).

![preview](preview.png)

## Usage

To use this wallpaper, you must first install the
[plasma5-wallpapers-dynamic](https://github.com/zzag/plasma5-wallpapers-dynamic)
plugin. Then download the
[HEIC file](https://github.com/subpop/fedora-kde-dynamic-wallpaper/blob/f35/f35-dynamic.heic)
and add it using the Plasma Wallpaper settings. The file is large; roughly 20MB
in size and has a resolution of 4032 x 3024.

Alternatively, you could generate the image file yourself. Clone the repository,
and run `kdynamicwallpaperbuilder` (available in the
[plasma5-wallpapers-dynamic](https://github.com/zzag/plasma5-wallpapers-dynamic)
project). The included HEIC file was run with the
following command:

```
kdynamicwallpaperbuilder --output f35-dynamic.heic --quality 100 metadata.json
```

## Credit

Artwork by the [Fedora Design Team](https://github.com/fedoradesign/)
