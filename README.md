# Xiaomi Global Themes · Theme Portfolio

Three complete themes for Xiaomi Global (HyperOS 3), each kept in its own folder with the same structure: preview frames, cover, README, verification record, layered PSD and the importable package.

## Index

| Folder | Theme | Direction | Preview |
| --- | --- | --- | --- |
| `主题/001 - 卡通 IP 形象主题` | Cocoa Bear | Plush bear IP, cream and maple-brown autumn palette | 640 × 1422 |
| `主题/002 - Moody Ocean 情绪海洋` | Moody Ocean | Cinematic grey-blue seascape, dynamic lock screen, frosted glass | 1080 × 2400 |
| `主题/003 - Siam Serenity` | Siam Serenity | Southeast Asian coastline, sunset coral and jungle emerald, dynamic lock screen with weather and calendar widgets | 1080 × 2400 |

```
主题/
├── 001 - 卡通 IP 形象主题/
│   ├── 01-lockscreen.jpg ~ 05-icons.jpg
│   ├── 封面.jpg
│   ├── README.md
│   ├── SUBMISSION_OS3.txt / checks.json / materials.json
│   └── cocoa-bear-theme_Layered_PSD.zip      # layered PSD archive
├── 002 - Moody Ocean 情绪海洋/
│   ├── 01-lockscreen.jpg ~ 05-icons.jpg
│   ├── 封面.jpg
│   ├── README.md
│   ├── Moody Ocean 情绪海洋.mtz                # importable theme package
│   └── Moody Ocean 情绪海洋_Layered_PSD.zip     # layered PSD archive
└── 003 - Siam Serenity/
    ├── 01-lockscreen.jpg / 01b-lockscreen-quiet.jpg / 02-home.jpg
    ├── 03-messages.jpg / 04-settings.jpg / 05-icons.jpg
    ├── 封面.jpg
    ├── README.md
    ├── VERIFICATION.txt                        # nine-patch scan, inventory, limitations
    ├── Siam Serenity.mtz                       # importable theme package, 8.9 MB
    └── Siam Serenity_Layered_PSD.zip           # 4 layered PSDs
```

## Notes

- All three packages target the Global channel: `resourceType=theme`, `uiVersion=17`, `miuiAdapterVersion=3.3`.
- `.mtz` files are standard zip containers (root `description.xml` + module folders + `preview/`) without a signature, intended for local import and Theme Editor testing on HyperOS 3 Global.
- Layered PSDs are 8-bit RGBA at 1080 × 2400 (001 keeps its original 640 × 1422 export size) and open directly in Photoshop or Affinity Photo.
- 003 ships a dynamic MAML lock screen (time- and sensor-driven motion, second quiet page, live weather and calendar widgets), 53 store-spec icons over 86 package names, rebuilt system panels, and SMS bubbles.

## License

Design and assets by kahao-git. For personal use and portfolio display; please do not resell or redistribute commercially.
