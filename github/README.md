# Github

Shows Github notifications and adds a shortcut to access your notifications. It uses hub for api interactions and api access.


# Dependencies

- [Hub](https://github.com/github/hub)
- [Font Awesome](https://fontawesome.com) for the Github icon.

# Usage

Clicking the Github icon will open the notifications Github panel.

# Config

```INI
[dunst]
command=$SCRIPT_DIR/dunst
interval=once
format=json
markup=pango
#min_width=50
#align=center
#DUNST_MUTE=off
```

