# Map Sprites



To generate the sprite sheet, run the following commands:

Install the package that will generate the sprite sheet.
```shell
npm i -g  @beyondtracks/spritezero-cli --force
```

Run the cmd, first arg is the filename of the output and second is the target folder with the icons.
```shell
spritezero sprite icons 
```

Please optimize your icons before push to this repo. An easy way to do this is use the following tool:

https://github.com/svg/svgo


```shell
# svgo -f <input folder> <output folder>
 svgo -f icons min 
```