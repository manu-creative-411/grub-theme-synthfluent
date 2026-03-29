# grub-theme-synthfluent

A simple grub theme which combines Hyperfluent with a synthwave aesthetic.

I created this theme in early 2024, when I discovered Hyperfluent and was overly hyped with synth/vaporwave  _a e s t h e t i c s_  for some reason.

Icons are based on `vimix-grub-theme`.

## How to install it

1. Clone this repo:

```bash
git clone https://github.com/manu-creative-411/grub-theme-synthfluent.git
```

2. Move the directory somewhere in your disk:

```bash
sudo mkdir -p /boot/grub/themes
sudo mv grub-theme-synthfluent /boot/grub/themes/synthfluent
```

⚠️ Have a second look on the final path. You will need it on the next step.

3. Config `grub` to use the theme:

```bash
sudo nano /etc/default/grub
```

```
# ADD/EDIT THIS LINE AND SET THE CORRECT PATH FOR THE THEME'S theme.txt:
GRUB_THEME=/boot/grub/themes/synthfluent/theme.txt
```

4. Save, exit and update `grub`

```bash
sudo update-grub # Debian/Ubuntu
# or
sudo grub2-mkconfig -o /boot/grub2/grub.cfg # Fedora
```

5. Reboot. That's all.
