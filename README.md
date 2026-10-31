# zen-customization

My CSS tweaks for [Zen Browser](https://zen-browser.app).

## Tweaks

- Scales down the sidebar using a `zoom` property.

## Install

1. In `about:config`, set `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`.
2. Open `about:support` and go to **Profile Folder** → **Open in Finder**.
3. Add the CSS as `chrome/userChrome.css` in that folder, creating `chrome` if needed. Either:
   - **Copy:** paste in the contents of `userChrome.css`.
   - **Link, to update with `git pull`:**

     ```bash
     ln -s ~/git/zen-mods/userChrome.css "<profile-folder>/chrome/userChrome.css"
     ```

4. Restart Zen.
