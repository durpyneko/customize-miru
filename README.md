# customize-miru
Customize the [Miru](https://github.com/ThaUnknown/miru) anime torrent streaming app

# Windows
1. have the app installed on you device
2. cd into Miru directory
```ps
cd ~/AppData/Local/Programs/Miru/resources
```
3. extract the bundled app.asar
 ```ps
npx @electron/asar extract app.asar .\unpacked
```
4. make your changes
5. rebuild
```ps
npx @electron/asar pack .\unpacked\ app.asar
```

# Linux
i don't know where Miru is located but should be similar to above steps

# MacOS
i don't know where Miru is located but should be similar to above steps

# Possible changes
you can experiment on your own but of what i can see
- fonts
- css
- html
- app icon
- app title (html tag <title> in app.html)
- some javascript maybe?
