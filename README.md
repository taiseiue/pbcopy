# pbcopy
pbcopy/pbpaste everywhere; with OSC52

### What's this?
This script uses OSC 52 to extend a copy and paste experience similar to pbcopy and pbpaste on macOS to Unix-compatible systems. By using this, you can copy and paste over SSH.

### Usage

Download the pbcopy and pbpaste code from this repository and add the directory to your PATH.

More simply, you can use it by running the following commands in order. However, please only use this if you understand what it does.

```bash
sudo -v
curl "https://github.com/taiseiue/pbcopy/blob/main/src/pbcopy"  | sudo tee /usr/local/bin/pbcopy  >/dev/null
curl "https://github.com/taiseiue/pbcopy/blob/main/src/pbpaste" | sudo tee /usr/local/bin/pbpaste >/dev/null
sudo chmod +x /usr/local/bin/pbcopy /usr/local/bin/pbpaste
```

### License
This software is released under the [The MIT License](./LICENSE).

Copyright (c) 2026 Taisei Uemura  
Released under the [MIT license](./LICENSE)

