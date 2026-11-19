# GlassItcord

A clean, minimal glass theme for Discord, inspired by [GlassIt-VSC](https://github.com/hikarin522/GlassIt-VSC).
One setting makes all of Discord see-through, while text and avatars stay sharp.

## Made for one monitor

No second screen? No problem. Put Discord on top of your game, video or browser and keep watching it **right through Discord** while you chat, follow a call or check a stream. No more alt-tabbing back and forth.

## Requirements

- [Vencord](https://vencord.dev) or [BetterDiscord](https://betterdiscord.app)
- Window transparency turned on in your mod's settings

## Install

1. Download `GlassItcord.theme.css`.
2. In Discord, open **Settings → Themes → Open Themes Folder** and put the file there.
3. Turn on **GlassItcord** in the theme list.
4. Turn on **window transparency** in your mod's settings.
5. Fully quit Discord from the tray icon and reopen it.

## Settings

Open the file in any text editor and change the values at the top. Save, and Discord updates instantly.

```css
--glass: 0.8;        /* 0 = fully transparent, 1 = solid */
--glass-tint: 0 0 0; /* glass colour as R G B */
```

| `--glass` | Look |
|-----------|------|
| `0.2` | Very clear, best for watching what's behind |
| `0.5` | Balanced, good for one monitor |
| `0.8` | Dark glass (default) |

Menus and popups are automatically a bit more solid, so they stay readable.

## Troubleshooting

- **Discord is dark but not see-through:** window transparency is off, or Discord wasn't fully restarted.
- **Nothing changes:** make sure the theme is turned on and you edited the file inside the themes folder.
- **Lag while gaming or streaming:** see-through windows use some graphics power. Raise `--glass` or turn off window transparency.

## Author

Made by **wolf4444**, with a little help from my one and only colleague, [Claude](https://claude.ai) 🤖.

## License

[MIT](LICENSE): free to use, change and share. Just keep the credit.
