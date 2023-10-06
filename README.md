# Map Sprites

To generate the sprite sheet, run the following commands:

The library bellow only works with node 8:

```shell
nvm install 8
nvm use 8
```

Install the package that will generate the sprite sheet.

```shell
npm i -g  @beyondtracks/spritezero-cli
```

Run the cmd, first arg is the filename of the output and second is the target folder with the icons.

```shell
spritezero sprite icons
```

**Retina Icons**

```shell
spritezero --retina sprite@2x icons
```

Please optimize your icons before push to this repo. An easy way to do this is use the following tool:

https://github.com/svg/svgo

```shell
# svgo -f <input folder> <output folder>
 svgo -f icons min
```
