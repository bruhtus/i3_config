# Qtile Window Manager Configuration

i3 is a tling window manager (usually called i3wm). The default configuration may vary depending on your distro, in my case the default configuration file is on $HOME/.i3/config (you can search using `locate .i3/config` but don't forget to do `sudo updatedb` first).
You can find the info about i3 on [their website](https://i3wm.org) or [their documentation](http://i3wm.org/docs/).

The component used in this config is:
- [pywal](https://github.com/dylanaraps/pywal)
- [polybar](https://github.com/polybar/polybar)
- [py3status](https://github.com/ultrabug/py3status)

You could change new terminal color scheme by adding pywal color scheme to you shell config (.bashrc or .zshrc or something else) by adding this command:
```bash
(cat ~/.cache/wal/sequences &)
cat ~/.cache/wal/sequences
source ~/.cache/wal/colors-tty.sh
```

File [startxrandr.sh](startxrandr.sh) is for setting up dual monitor with xrandr.
