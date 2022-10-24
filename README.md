# Windows Terminal Ubuntu Theme

<img width="1177" alt="image" src="https://user-images.githubusercontent.com/12980409/197592440-64686f3a-9049-4d88-b16c-941f6718ab65.png">

# Steps

1. Open Windows Terminal (install from Microsoft Store if under Windows 11).
2. Open `Settings > Open JSON file`.
3. Add below to the "schemes" entry.

```json
        {
            "background": "#300A24",
            "black": "#2E3436",
            "blue": "#3465A4",
            "brightBlack": "#555753",
            "brightBlue": "#729FCF",
            "brightCyan": "#34E2E2",
            "brightGreen": "#8AE234",
            "brightPurple": "#EF50EF",
            "brightRed": "#EF2929",
            "brightWhite": "#EEEEEC",
            "brightYellow": "#FFE94F",
            "cursorColor": "#BBBBBB",
            "cyan": "#06989A",
            "foreground": "#EEEEEC",
            "green": "#4EA406",
            "name": "Ubuntu",
            "purple": "#75500D",
            "red": "#CC0000",
            "selectionBackground": "#FFFFFF",
            "white": "#D3D7CF",
            "yellow": "#C4A000"
        },
```

4. In the `Settings`, select one of the profiles (Windows PowerShell or Ubuntu-22.04).
5. Go to `Appearance`.
6. 
  - Color scheme: `Ubuntu`
  - Font face: `UbuntuMono NF` (install Nerd Font)
  - Cursor shape: `Filled box`
  - Intense text style: `Bold font with bright colors`
  
# References
- https://learn.microsoft.com/en-us/windows/terminal/custom-terminal-gallery/custom-schemes (They have the Raspberry Ubuntu theme, which looks different.)
