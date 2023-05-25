# eu.ad5001.LogarithmPlotter

Flahub repository for [LogarithmPlotter](https://apps.ad5001.eu/logarithmplotter/).

## KF6

The files in the `kf6` directory contain the most barebones instalations of the KDE Frameworks 6 to install the QtQuick Controls 2 Desktop Theme or Breeze Styles. They're not used in LogarithmPlotter for now, as the cost vs benefits ratio is minimal (longer load times against slightly higher fidelity to KDE desktop theme, but still no theme awareness, or proper breeze icons integration)

## Build

You can build the latest version of LogarithmPlotter flatpak using `flatpak-builder`:    
```bash
flatpak-builder AppDir eu.ad5001.LogarithmPlotter.json
```

After it finishes building (note that this step can take a while as it compiles Qt), you can run it using:    
```bash
flatpak-builder --run AppDir/ eu.ad5001.LogarithmPlotter.json logarithmplotter --no-check-for-updates
```
