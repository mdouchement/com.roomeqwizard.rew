# REW - Room EQ Wizard

This repository is a quick working packaging of REW in Flatpak.\
It does not follow the conventions of flathub.org builds (using a shared JVM package, providing a .desktop file, and so on).

```sh
flatpak-builder build-dir com.roomeqwizard.rew.yml --force-clean
```

```sh
flatpak-builder --user --install --force-clean build-dir com.roomeqwizard.rew.yml
```

```sh
flatpak run com.roomeqwizard.rew
```
