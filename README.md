# com.gluonhq.scenebuilder
Flatpak for [Scene Builder](https://gluonhq.com/products/scene-builder)

## Prerequisite

- `flatpak`, `flatpak-builder` packages
- Runtime `org.freedesktop.Platform` version `22.08`
- Runtime `org.freedesktop.Sdk` version `22.08`

### Build and install Scene Builder
```
flatpak-builder --user --install --force-clean  flatpakbuildir com.gluonhq.scenebuilder.yaml
```
### Run Scene Builder
```
flatpak run com.gluonhq.scenebuilder
```
### Uninstall Scene Builder
```
flatpak uninstall --user com.gluonhq.scenebuilder
```