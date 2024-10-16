# Vyntra

Vyntra is a fork of (Vesktop)[https://github.com/Vencord/Vesktop], a custom Discord desktop app

**Main features**:
- Vencord preinstalled
- Much more lightweight and faster than the official Discord app
- Linux Screenshare with sound & wayland
- Much better privacy, since Discord has no access to your system

**Whats different?**
- Fixes Vesktop Issue: (#616)[https://github.com/Vencord/Vesktop/issues/161]

## Building from Source

Packaging will create builds in the dist/ folder

```sh
git clone https://github.com/Justus0405/Vyntra
cd Vyntra

# Install Dependencies
pnpm i

# Either run it without packaging
pnpm start

# Or package
pnpm package
# Or only build the pacman target
pnpm package --linux pacman
# Or package to a directory only
pnpm package:dir
```