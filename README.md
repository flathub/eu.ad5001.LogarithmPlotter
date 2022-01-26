# eu.ad5001.LogarithmPlotter

Flahub repository for [LogarithmPlotter](https://apps.ad5001.eu/logarithmplotter/).

## Build

You can build the latest version of LogarithmPlotter flatpak using `flatpak-builder`:    
```bash
flatpak-builder AppDir eu.ad5001.LogarithmPlotter.json
```

After it finishes building (note that this step can take a while as it compiles Qt), you can run it using:    
```bash
flatpak-builder --run AppDir/ eu.ad5001.LogarithmPlotter.json logarithmplotter --no-check-for-updates
```
