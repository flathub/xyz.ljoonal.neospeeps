# NeosPeeps flathub edition

NeosPeeps is tool that allows for listing your [NeosVR](https://steamcommunity.com/app/740250) friends quickly, without having to actually open the whole game. For more details, go to <https://neos.ljoonal.xyz/peeps>.

## Release checklist

1. Run release script on gitea & publish release
2. Switch to this repo
3. Update manifest file's tag & commit
4. Create [`generated-sources.json`](https://github.com/flatpak/flatpak-builder-tools/tree/master/cargo), commit & push

```sh
python3 flatpak-cargo-generator.py ~/Repos/git.ljoonal.xyz/ljoonal/NeosPeeps/Cargo.lock
```
