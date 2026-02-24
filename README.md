# Alpine in Browser

Single-file project that boots Alpine Linux in your browser using v86.

This repo now includes all required VM assets locally:

- v86 runtime JS
- v86 WebAssembly payload
- SeaBIOS + VGA BIOS
- Alpine Linux ISO

Current bundled Alpine ISO:
- `alpine-virt-3.23.3-x86_64.iso`

No external network calls are required at runtime.

## Your Flow

1. Download the repository ZIP from GitHub.
2. Unzip it.
3. Open `index.html` in your browser.
4. Click **Start Alpine VM**.

## Notes

- First boot can take a little time while the browser decodes bundled assets.
- Use the VGA panel as the primary console.
- The project is intentionally large because VM binaries are bundled.
- If package repositories are stale, use the **Fix APK Repos** button in the UI after logging in.
