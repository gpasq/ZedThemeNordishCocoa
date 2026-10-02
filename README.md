# NordishCocoa for Zed

<img width="2672" height="1458" alt="Zed 2026-10-02 11 49 19" src="https://github.com/user-attachments/assets/a2bc96db-164c-435e-b4a7-34b24ba750ae" />



NordishCocoa takes the basic Nord editing theme and wraps it in a comfy, earthy, cocoa blanket. The result
is a theme that is as easy on the mind as it is easy on the eyes. As beautiful and restful as it is useful.

This is the [Zed](https://zed.dev) port of the
[NordishCocoa theme for Visual Studio Code](https://github.com/gpasq/VisualStudioCodeThemeNordishCocoa).

## Themes

- **NordishCocoa** — the original dark theme.
- **NordishCocoa Blurred** — the same colors over a translucent, blurred window background.

## Installing

### From the Zed extension registry

1. Open the extensions view (`zed: extensions` in the command palette).
2. Search for **NordishCocoa** and click **Install**.
3. Run `theme selector: toggle` and pick **NordishCocoa**.

### As a dev extension (local checkout)

1. Clone this repository.
2. In Zed, run `zed: install dev extension` and select the cloned folder.
3. Run `theme selector: toggle` and pick **NordishCocoa**.

To make it the default, add this to your Zed `settings.json`:

```json
{
  "theme": "NordishCocoa"
}
```

## Publishing a new version

1. Bump `version` in `extension.toml` and push to GitHub.
2. In a fork of [zed-industries/extensions](https://github.com/zed-industries/extensions), add or update this
   repository as a submodule under `extensions/nordish-cocoa`, and set the matching `version` for
   `[nordish-cocoa]` in `extensions.toml`.
3. Run `pnpm sort-extensions` and open a pull request.

## License

[MIT](LICENSE) © Greg Pasquariello / [Tecnicl.com](https://tecnicl.com)

**Enjoy!**
