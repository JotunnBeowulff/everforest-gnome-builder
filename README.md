# Everforest for [Gnome Builder](https://wiki.gnome.org/Apps/Builder)
## Preview (together with the Everforest Libadwaita theme)
![Screenshot from 2022-12-20 12-58-16](https://user-images.githubusercontent.com/62945074/208661810-2e263663-9ae0-40d2-866b-810218b02dcb.png)

## Installation
### In newer versions of Builder
#### The graphical way
1. Download the XML file
2. Open Builder and click 'Preferences' > 'Appearance'
3. Go to the 'Color' section
4. Drag and drop the downloaded file from Files to there. It should be available now.
#### With the terminal
Run 
```bash
mkdir -p ~/.local/share/gtksourceview-5/styles && curl -o ~/.local/share/gtksourceview-5/styles/Everforest\ Medium\ Dark.xml "https://raw.githubusercontent.com/ghostcrafter551/everforest-gnome-builder/main/everforest-medium-dark.xml"
```
in your terminal **OR**:
1. Download the XML file
2. Copy it to `~/.local/share/gtksourceview-5/styles/` or `~/.var/app/org.gnome.Builder/config/gtksourceview-5/styles/`

### In older versions
1. Download the XML file
2. Copy it to `~/.local/share/gtksourceview-3.0/styles/` or `~/.var/app/org.gnome.Builder/config/gtksourceview-3.0/styles/`
3. Restart Builder (if running) and select the theme.
