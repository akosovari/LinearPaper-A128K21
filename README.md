# LinearPaper based fork specificly designed to run on a128k21.org.

Xymb's Linear region file format uses about half of the original Anvil region file without any loss of data.
Check [this repository for documentation and tools](https://github.com/xymb-endcrystalme/LinearRegionFileFormatTools).


## Compiling

```
./gradlew applyPatches
./gradlew createReobfPaperclipJar
```

Your compiled .jar will be in `build/libs/`.
