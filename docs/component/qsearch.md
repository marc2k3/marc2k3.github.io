# QSearch
[Download :material-download:](https://github.com/marc2k3/marc2k3/releases){ .md-button }

## Usage
This provides 6 context menu items to create playlists or open a search window
from the selected track's metadata.

```
artist IS
title IS
album IS
artist HAS
title HAS
album HAS
```

If you look under `File>Preferences>Advanced>Tools>QSearch`, there are 5 options.

```
Create Autoplaylist
Create Autoplaylist and switch
Send search results to standard playlist
Send search results to standard playlist and switch
Open Media Library search window
```

!!! note
	If you hold the ++shift++ key when selecting a menu item, it will always open the `Media Library` search window.

## Changes

### 1.0.11
- Another double quote related bug fix with `HAS`.

### 1.0.10
- Improve handling of searches containing double quotes which was poorly implemented in the previous release!

### 1.0.9
- Workaround an issue where metadata containing double quotes could not be found. Instead of using
`field IS` / `field HAS`, `$stricmp` and `$strstr` are used instead.

### 1.0.8
- Compiled with latest `foobar2000` `SDK`.
- The minimum requirement is now `foobar2000` `2.1`.
