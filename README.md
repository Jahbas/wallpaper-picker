# wallpaper-picker

Simple GTK wallpaper picker for `hyprpaper` on Hyprland.

![Image picker cutout](imgs/image.png)

![Fullscreen view](imgs/image2.png)

It loads wallpapers from `~/Pictures/Wallpapers` and sets the one you click.

Use it with a Hyprland `SUPER` hotkey so the picker opens fast.

If you have more than 3 wallpapers, you can scroll to move through more.

## Run

```bash
./wallpaper-picker
```

## Notes

Requires Python, GTK 3 (`PyGObject`), and `hyprpaper`.

Save your wallpaper images in `~/Pictures/Wallpapers` by default.

If you want to use a different folder, change `WALLPAPER_DIR` in `wallpaper-picker`.
