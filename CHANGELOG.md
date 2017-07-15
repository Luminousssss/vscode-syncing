# Changelogs

## 1.4.2 - July 15, 2017

- Added: Show remote Gist list when uploading/downloading for the first time, makes it easier to use. But also, low speed network will make it suffer. Please use proxy (Thanks [@Henry Li](https://github.com/MagicCube) for the advice).
- Added: Add `Getting Started` in `README`.
- Changed: Tweak error handlers and toasts.


## 1.4.1 - July 12, 2017

- Changed: First attempt to change the logo.


## 1.4.0 - July 12, 2017

- Fixed: Image URLs are now resolved to `https` URLs as required by VSCode-1.14.


## 1.3.9 - June 9, 2017

- Fixed: Using extension's local version to properly remove the old extensions.


## 1.3.8 - May 15, 2017

- Changed: Tuning the timeout threshold to reduce the connection failures on slow networks.


## 1.3.7 - May 4, 2017

- Fixed: Reset Keyboard-Shortcuts image size.


## 1.3.6 - May 4, 2017

- Changed: Resize Keyboard-Shortcuts image.


## 1.3.5 - May 4, 2017

- Changed: Update guides.


## 1.3.4 - April 7, 2017

- Fixed: Minor fixes to the Downloading and Uploading features.


## 1.3.3 - March 3, 2017

- Fixed: Checking user access privileges when uploading.


## 1.3.2 March 2, 2017

- Changed: Update the messages of `Settings File Not Found` and `Setting File Invalid` errors.
- Fixed: Upload an `empty array` (instead of `null`) when extension list is empty, to avoid potential error.


## 1.3.1 - February 21, 2017

- Fixed: Message error of Download dialog.


## 1.3.0 - February 21, 2017

- Changed: Upload and Download dialogs.
- Changed: Separate error messages of invalid GitHub Personal Access Token and Gist ID.
- Changed: User Guide.


## 1.2.9 - February 8, 2017

- Added: Clean up temporary files automatically.
- Changed: Pretty JSON files: `extensions.json`, `syncing.json`, make it a little more user-friendly (Thanks [@fengcen](https://github.com/fengcen) for the advice).


## 1.2.8 - December 30, 2016

- Changed: User Guide.


## 1.2.7 - December 30, 2016

- Fixed: Ignore `null` content to avoid node-github error.


## 1.2.6 - November 10, 2016

- Fixed: Reload dialog isn't shown when extensions are changed.


## 1.2.5 - November 9, 2016

- Added: Hints of the synchronization.
- Added: Show reload dialog when extensions are changed.
- Added: Support download settings from public Gist.
- Fixed: Synced extensions aren't managed by vscode.
