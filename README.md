# GitHub Dark Theme for Notepad++

[![License: MIT](https://img.shields.io/badge/License-MIT-3fb950.svg)](LICENSE)
[![Notepad++](https://img.shields.io/badge/Notepad%2B%2B-8.9.8.1%20tested-90c53f.svg)](https://notepad-plus-plus.org/)

Bring the familiar look of GitHub Dark to Notepad++.

This theme combines GitHub's deep background, crisp text, and carefully balanced syntax colors with the speed and simplicity of Notepad++. It is designed to stay readable during long coding sessions without losing the visual character developers know from GitHub.

![GitHub Dark theme running in Notepad++](Screenshot.jpg)

## Highlights

- Faithful GitHub Dark-inspired color palette
- Broad syntax coverage with styles for 92 language lexers
- Comfortable contrast for long editing sessions
- Matching editor details, including selections, line numbers, indentation guides, and code folding
- Tested with Notepad++ 8.9.8.1
- No plugin required

## Installation

1. Download [`GitHubDark.xml`](GitHubDark.xml).
2. Close Notepad++ if it is running.
3. Copy `GitHubDark.xml` into the appropriate `themes` folder:

   **Standard installation**

   ```text
   %AppData%\Notepad++\themes\
   ```

   **Portable installation**

   ```text
   <your Notepad++ folder>\themes\
   ```

4. Open Notepad++.
5. Go to **Settings → Style Configurator**.
6. Select **GitHubDark** from the **Select theme** list.
7. Click **Save & Close**.

That is it—open a source file and enjoy a cleaner, GitHub-inspired workspace.

> [!TIP]
> For the most consistent appearance, enable the Notepad++ interface dark mode under **Settings → Preferences → Dark Mode**.

## Updating

Download the newest `GitHubDark.xml`, replace the existing file in your `themes` folder, and restart Notepad++.

## Troubleshooting

If **GitHubDark** does not appear in the theme list:

- Make sure the file is named exactly `GitHubDark.xml` and not `GitHubDark.xml.txt`.
- Confirm that it is inside the correct `themes` folder.
- Restart Notepad++ after copying or replacing the file.

## Customization

You can fine-tune individual colors and fonts from **Settings → Style Configurator**. Keep a backup of your customized XML before updating the theme, because replacing the file will overwrite local changes.

## Credits

The palette is inspired by the [GitHub Dark style for highlight.js](https://github.com/highlightjs/highlight.js/blob/main/src/styles/github-dark.css) and adapted to the Notepad++ editor and lexer model.

Created and maintained by **Tom Papatolis**.

## License

Original work in this repository is released under the [MIT License](LICENSE). Copyright © 2026 Tom Papatolis.

`GitHubDark.xml` is based on upstream Notepad++ theme resources and retains the applicable attribution and licensing notice in its source header.
