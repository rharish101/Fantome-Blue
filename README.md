## Introduction
Just a messy edit of Fantome, by [addy-dclxvi](https://github.com/addy-dclxvi), which is a messy edit of the Arc GTK theme.
I liked the simplicity of Fantome, but I wanted the colorscheme of Arc-Dark.
Therefore, I created this variant.

Install this theme as follows:
```
mkdir -p ~/.themes
cd ~/.themes
git clone https://github.com/rharish101/Fantome-Blue
```

This theme contains a metacity theme (for window decorations) with the title hidden.
It also contains a theme for plank, and a few gtk3 changes made to Whisker Menu, as per my taste.
The scrollbar for GTK+3 is also squarer than the original.

## Metacity Theme
In order to use the metacity theme, you need to symlink this repository to either `$HOME/.local/share/themes` or `/usr/share/themes` (for a system-wide installation).
This is because of this [bug](https://bugzilla.redhat.com/show_bug.cgi?id=952854).

## Plank Theme
To install the Plank theme, copy the `plank` folder as `Fantome-Blue` to `~/.local/share/plank/themes` or to `/usr/share/plank/themes` for system-wide use.
Now open the Plank preferences window by executing plank --preferences from a terminal and select Fantome-Blue as the theme.

## Preview
I use Compiz as my window manager.
The icons theme used is Arc-X-D, with Paper as a fallback.
Metacity theme is Arc-Dark.

### Thunar
![thunar](https://raw.githubusercontent.com/rharish101/Fantome-Blue/master/thunar.png)

### Xfce Settings
![xfce-settings](https://raw.githubusercontent.com/rharish101/Fantome-Blue/master/xfce-settings.png)

### Theme Chooser
![theme-chooser](https://raw.githubusercontent.com/rharish101/Fantome-Blue/master/theme-chooser.png)

### Pavucontrol
![pavucontrol](https://raw.githubusercontent.com/rharish101/Fantome-Blue/master/pavucontrol.png)

### Whisker Menu
![whisker-menu](https://raw.githubusercontent.com/rharish101/Fantome-Blue/master/whisker-menu.png)

## Installation
Simply just clone this repository to your ~/.themes folder.
```
git clone https://github.com/rharish101/Fantome-Blue ~/.themes
```
Then apply your desired theme using LXAppearance or Xfce4 Settings Appearance.

Failed to clone? Remove the *.git* folder inside the ~/.themes folder first

## Notes (from original Fantome)

- Panel frame is a bloat, so I remove it.

- Combo entry is a bloat, so I remove it. But don't worry, there will be an outline when it's selected.

- Scrollbar placeholder is a bloat, so I remove it. Don't worry, the scrollbar itself remains visible.

- Progressbar placeholder is a bloat, so I remove it. Don't worry, the progressbar itself remains visible.

- Tab button is a bloat, so I replace it with simple underline for top and bottom tab. And sideline for left and right tab.

- Multiple background colour is a bloat, so I unify the colour. #ffffff for light theme and #2f343f for dark theme.

- Button actually is a bloat, previously I completely remove the Button Pixmap. 
But it breaks my workflow, especially when I deal with an app with so many buttons like GIMP. 
So, now I made the button only visible as a thin outline for inactive button. And slight highlight for active button.

- GTK CSD is the best example of bloat. It breaks some compositing effect, like multiple shadow, wrong transparency, and having hide, maximize, & close buttons in tiling window manager which is ridiculous. 
I recommend You to remove it using gtk-nocsd (╯°□°）╯︵ ┻━┻

- Just like any dark theme. Sometimes it breaks web browsing experience, and I don't know how to fix it.

- I designed this theme for myself. So I use "It works for me" philosophy. Don't complain if it doesn't work for You :p

## License

GPL of course, feel free to modify and share this theme ;)
