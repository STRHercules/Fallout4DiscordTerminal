<div align="center">

<a href="https://github.com/STRHercules" target="_blank">
  <img src="https://img.shields.io/badge/GitHub-Profile-0b0f0b?style=for-the-badge&logo=github&logoColor=9eef98&labelColor=050805"/>
</a>

<a href="https://store.steampowered.com/app/4458750/Wardens_of_Wen/" target="_blank">
  <img src="https://img.shields.io/badge/Wardens%20of%20Wen-On%20Steam-0b0f0b?style=for-the-badge&logo=steam&logoColor=9eef98&labelColor=050805"/>
</a>

<a href="https://linktr.ee/wardensofwen" target="_blank">
  <img src="https://img.shields.io/badge/Linktree-Links-0b0f0b?style=for-the-badge&logo=linktree&logoColor=9eef98&labelColor=050805"/>
</a>

<a href="https://discord.gg/XRnuHY5uuS" target="_blank">
  <img src="https://img.shields.io/discord/1441671903948439595?label=Discord&logo=discord&style=for-the-badge&color=0b0f0b&labelColor=050805&logoColor=9eef98"/>
</a>

</div>

<br/>

<div align="center">

```text
╔══════════════════════════════════════════════════════════════╗
║                                                              ║
║              ROBCO INDUSTRIES TERMINAL INTERFACE             ║
║                                                              ║
║                  FALLOUT 4 TERMINAL THEME                    ║
║                                                              ║
║                    STATUS: ONLINE                            ║
║                    BUILD:  RESTORED                          ║
║                    THEME:  TERMINAL GREEN                    ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝
```

</div>

<p align="center">
  <img src="Screenshots/Main.png" alt="Fallout 4 Terminal Theme Main Screenshot">
</p>

<p align="center">
  <img src="Screenshots/Settings.png" alt="Fallout 4 Terminal Theme Settings Screenshot">
</p>

---

```text
> ABOUT
```

This is my first Discord theme, though you may not even be able to call it that.

I restored and fixed several broken parts of the original theme, then added extra styling passes to make Discord feel more like a complete Fallout-style terminal interface.

The restored version includes:

```text
[✓] Terminal green UI colors
[✓] Standalone local CSS build
[✓] Settings page skinning
[✓] Vencord settings support
[✓] Menu and popout styling
[✓] CRT scanline overlay
[✓] Discord titlebar and toolbar fixes
[✓] Bottom-left user panel fixes
[✓] Optional all-green text mode
```

---

```text
> INSTALLATION
```

Installing BetterDiscord themes is straightforward:

```text
1. Open Discord settings
2. Go to "Themes"
3. Click "Open Theme Folder"
4. Move the downloaded .theme.css file into that folder
5. Enable the theme from Discord's theme list
```

For Vencord:

```text
1. Open Discord settings
2. Go to Vencord > Themes
3. Click "Open Themes Folder"
4. Move the .theme.css file into that folder
5. Click "Load missing Themes"
6. Enable the theme
```

---

```text
> CUSTOMIZATION
```

You can customize the theme by editing the variables inside the `.theme.css` file.

<p align="center">
  <img src="Screenshots/Variables.png" alt="Theme Variables Screenshot">
</p>

Main color variables:

```css
:root,
.visual-refresh,
.visual-refresh.theme-dark {
  --rgb-highlight: 74, 239, 152;
  --rgb-background: 0, 9, 0;
  --rgb-text: 158, 239, 152;
  --rgb-close-button: 212, 18, 39;
}
```

To restore full all-green text, uncomment the optional green text block:

<p align="center">
  <img src="Screenshots/Block.png" alt="Green Text Block Screenshot">
</p>

```css
[class*="messageContent_"] {
  color: rgb(var(--rgb-text)) !important;
}
```

---

```text
> FONT
```

This theme is designed around:

```text
DepartureMono Nerd Font
```

Recommended local font stack:

```css
--departure-font:
  "DepartureMono Nerd Font",
  "DepartureMono Nerd Font Mono",
  "Departure Mono Nerd Font",
  monospace;
```

GitHub README files cannot force this font globally, but the actual Discord theme can.

---

```text
> NEED MORE HELP?
```

Join my Discord server for support and customization help:

<a href="https://discord.gg/XRnuHY5uuS" target="_blank">
  <img src="https://img.shields.io/badge/Discord-Theme%20Support-0b0f0b?style=for-the-badge&logo=discord&logoColor=9eef98&labelColor=050805"/>
</a>

---

```text
> WANT TO SUPPORT ME?
```

Buy my game on Steam:

<a href="https://store.steampowered.com/app/4458750/Wardens_of_Wen/" target="_blank">
  <img src="https://img.shields.io/badge/Wardens%20of%20Wen-On%20Steam-0b0f0b?style=for-the-badge&logo=steam&logoColor=9eef98&labelColor=050805"/>
</a>

Join the Wardens of Wen Discord server:

<a href="https://discord.gg/wNkKJES6QY" target="_blank">
  <img src="https://img.shields.io/badge/Wardens%20of%20Wen-Discord-0b0f0b?style=for-the-badge&logo=discord&logoColor=9eef98&labelColor=050805"/>
</a>

---

```text
> CREDITS
```

The original theme was made by:

<a href="https://github.com/B4T3S/Fallout4TerminalTheme" target="_blank">
  <img src="https://img.shields.io/badge/B4T3S-Original%20Theme%20Author-0b0f0b?style=for-the-badge&logo=github&logoColor=9eef98&labelColor=050805"/>
</a>

---