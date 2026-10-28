# LiLi Native — Homebrew tap

Install the native LinuxLive USB Creator edition maintained by Enrique (Coolestcool):

```sh
brew tap Coolestcool/lili
brew install lili
```

Update with `brew update` and `brew upgrade lili`. `lili` is an alias for the `linuxlive-usb-creator` package and launcher.

[Application source, notices and releases](https://github.com/Coolestcool/linuxlive-usb-creator-native).
The current preview targets Intel macOS 26+ and Ubuntu/Debian x86_64. On Ubuntu/Debian, the `.deb` resolves desktop dependencies automatically. QEMU is optional for USB creation and required for launching Linux in a virtual machine.

Contact: [enrique330@gmail.com](mailto:enrique330@gmail.com).
This custom tap is separate from Homebrew's central catalog. Formula code is GPL v3; application and dependency notices accompany the application source.
