# Favicon
Favicon configuration files for [Icon Slate](http://www.kodlian.com/apps/icon-slate). To be used together with [Sketch](http://bohemiancoding.com/sketch/) and [IconSlate-sketchplugin](https://github.com/kodlian/iconslate-sketchplugin).

## Guide
Add your graphic to every Artboard in `favicons.sketch`. Run `Plugins/Icon Slate/Export Current Page's Artboards (Artboards combined)`. This will open up Icon Slate. Click the Settings icon in the top left corner and choose `Load a Configuration` and locate the configuration file you want to use. Click `Export` and choose where you want to save the favicons and click `Build`.

## Configurations

* `favicons.iconsconf`
* `favicon-ico.iconsconf`
* `favicon-standard.iconsconf`

## favicons.iconsconf

### Sizes
* 152x152
* 144x144
* 120x120
* 64x64
* 48x48
* 32x32
* 16x16

### Output
* favicon-152x152.png
* favicon-144x144.png
* favicon-120x120.png
* favicon.ico (a combined file with the `64x64`, `48x48`, `32x32` and `16x16` artboards)

## favicon-ico.iconsconf

### Sizes
* 64x64
* 48x48
* 32x32
* 16x16

### Output
* favicon.ico (a combined file with the `64x64`, `48x48`, `32x32` and `16x16` artboards)

## favicon-standard.iconsconf

### Sizes
* 32x32
* 16x16

### Output
* favicon.ico (a combined file with the `32x32` and `16x16` artboards)

## TODO
Add a configuration file for all sizes listed in [favicon-cheat-sheet](https://github.com/audreyr/favicon-cheat-sheet/blob/master/README.rst).
