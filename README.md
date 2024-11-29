# firefox vertical tabs autohide

simple userchrome css that automatically expands firefox's vertical tabs sidebar on hover.

![Animation](https://github.com/user-attachments/assets/10af0732-7749-4b4a-88b7-667dc389895e)

## how

use firefox nightly to get the window controls on the same row as the url bar.

type `about:config` in the url bar and enable these options:

- `sidebar.revamp`
- `sidebar.verticalTabs`
- `devtools.chrome.enabled`
- `toolkit.legacyUserProfileCustomizations.stylesheets`
- `devtools.debugger.remote-enabled`

then open your firefox profile folder (help -> more troubleshooting information -> profile folder)

create a new folder called `chrome` if it doesn't exist, and move `userChrome.css` inside.
