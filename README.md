# Fallout 4 Terminal Theme for BetterDiscord

A high-fidelity **Fallout 4 Terminal** custom theme for BetterDiscord, designed to transform your Discord interface into a retro-futuristic ROBCO Industries operating system.

This repository features local patches and modern layout fixes specifically updated to support Discord's **Visual Refresh UI**, stripping away unwanted native containers, header borders, and background box artifacts for a clean, borderless terminal experience.
<img width="1905" height="1043" alt="image" src="https://github.com/user-attachments/assets/59c6d4f4-ed7e-4cb6-9173-2d18acebda42" />

---

## Features

* **ROBCO Industries Aesthetic:** Implements authentic phosphor color palettes (Classic Amber/Green) complete with monospace typography (`Consolas`, `Courier New`).
* **CRT Scanline Overlay:** Subtle scanline gradients and atmospheric glow shaders across the app layout.
* **Visual Refresh Compatibility:** Fully patched to override modern Discord UI changes, eliminating persistent header dividers, "boost goal" banners, and redundant container background boxes.
* **Borderless Custom Layouts:** Strips away native container backgrounds behind server headers and channel lists, ensuring elements float seamlessly over the terminal backdrop.
* **Custom Top Title Bar:** Replaces the native header with a custom branded `ROBCO Industries (tm) - Terminal Link` status bar.

---

## Installation

1. Make sure you have [BetterDiscord](https://betterdiscord.app/) installed.
2. Download or copy the `Fallout4Terminal.theme.css` file from this repository.
3. Place the file into your BetterDiscord themes folder:
* **Windows:** `%appdata%\BetterDiscord\themes`


4. Open Discord, navigate to **User Settings > Themes**, and toggle the theme on.

---

## Customization

You can easily customize the color variables at the top of the CSS file (`:root` selector) to adjust highlight glows, backgrounds, and status colors to your preference:

```css
:root,
.visual-refresh,
.visual-refresh.theme-dark {
  --rgb-highlight: 74, 239, 152; /* Terminal Glow / Text */
  --rgb-background: 4, 12, 6;     /* Main App Background */
  --rgb-text: 74, 239, 152;       /* General Text Color */
}

```

---

## Changelog & Recent Patches

* **v4.5.5:** Targeted and isolated rogue internal anonymous wrapper layers within the channel list container to completely eradicate stubborn overlay blocks.



* **v4.5.0 - v4.5.4:** Restored natural server header padding and layout flow while purging native background ghost boxes and text-clipping issues.
* **Visual Refresh Update:** Overhauled container selectors to ensure full compatibility with Discord's layout updates.
