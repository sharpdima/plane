Vazirmatn local font instructions

This folder is for local Vazirmatn font files (woff2). The repository references these files from
`packages/propel/src/styles/fonts/index.css` via @font-face rules.

Expected filenames (place under this folder):
- Vazirmatn-300.woff2
- Vazirmatn-400.woff2
- Vazirmatn-500.woff2
- Vazirmatn-700.woff2

How to add the fonts (example PowerShell):

# Download example (only if you have a valid source/license). Replace <URL> with the actual file URL.
# Example (PowerShell):
# Invoke-WebRequest -Uri "https://example.com/path/to/Vazirmatn-400.woff2" -OutFile "./packages/propel/src/styles/fonts/Vazirmatn/Vazirmatn-400.woff2"

If you don't have local copies yet, you can temporarily use Google Fonts by uncommenting the import in `packages/propel/src/styles/fonts/index.css`.

License note: Ensure you have the right to redistribute the Vazirmatn files in this repository. If distribution isn't allowed, consider keeping them out of the repo and loading them from a secure internal CDN or the user's environment.
