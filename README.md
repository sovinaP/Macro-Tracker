# NourishOS v0.7 Alpha

NourishOS is a single-file nutrition tracker focused on fast daily logging, local storage, macro tracking, water tracking, weight tracking, quick foods, meal templates, goal setting, and USDA / Open Food Facts search.

## What changed in this version

- Themes now work as actual UI presets instead of just changing button labels.
- Light and Dark are no longer separate theme choices in the Themes row.
- Appearance now controls Light mode and Dark mode by itself.
- Themes now only contains the theme families, such as Forest, Sunset, and Slate.
- Each theme family adapts to both Light and Dark mode.
- The active theme button styling was cleaned up so it stays readable in both modes.
- A null-safe fix was added for the micro modal event binding so missing modal elements do not break the UI.

## Theme behavior

Use the Appearance button to switch between Light mode and Dark mode.
Then choose a theme family from the Themes row.
The selected family will automatically adapt to the current mode, so Forest in Light mode and Forest in Dark mode are both supported.

## Files to upload to GitHub

- `index-1.html` or your current main HTML build.
- This README file.

## Notes

- The app stores data locally in the browser.
- Backup and restore are handled through the Export backup and Import backup buttons.
- The micro nutrient drawers and modal are still supported, but the modal binding now fails safely if the element is missing.
