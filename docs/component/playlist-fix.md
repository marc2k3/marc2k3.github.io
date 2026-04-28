# Playlist Fix

## Requirements
- `foobar2000` `2.24` or later. 32bit and 64bit are both supported.
- `Windows 10` or later

[Download :material-download:](../files/foo_playlist_fix-1.5.fb2k-component){ .md-button .md-button--primary }

## Support
https://hydrogenaud.io/index.php/topic,123055.0.html

## Overview
This aims to provide similar functionality to `foo_playlist_revive`. It uses
title formatting to match dead playlist items against library items and updates
the playlist entries.

## Usage
Before using, check the main `Preferences>Tools>Playlist Fix`. You can view/add your
own title formatting presets.

There are 4 main menu commands under `File>Playlist Fix`.

```
Fix active playlist
Fix all playlists
Check active playlist
Check all playlists
```

!!! note
	The `check` options will generate a report without making any changes.

Because playlist operations are only permitted in the main thread, it may appear
to block the UI if used on large libraries/playlists. There is no way around that.

The report may look something like [this](../images/playlist-fix.png).

## Changes

### 1.5
- Maybe fix long path issue.

### 1.4
- Minor internal improvements.

### 1.3
- Preemptively fix compatibility with the next `foobar2000` release. Previous
versions may no longer work at all so updating is strongly recommended.

### 1.2
- Bump minimum requirements to `foobar2000` `2.24` and `Windows 10`.
- Compiled with the latest `foobar2000` `SDK`.

### 1.1.6
- The minimum requirement is now `foobar2000` `2.1`.
- Compiled with the latest `foobar2000` `SDK`.

### 1.1.5
- Internal changes only.

### 1.1.4
- Compiled with the latest `foobar2000` `SDK`.

### 1.1.3
- The report dialog has been updated so both path columns are auto-sizing. Also, the paths are no longer prefixed with `file://`.

### 1.1.2
- Fixes a bug where the report dialog list control had an ugly white border in `Dark Mode`.

### 1.1.1
- The report dialog is now resizeable.

### 1.1.0
- You can now save your own `Presets` under `File>Preferences>Tools>Playlist Fix`. The old setting under `Advanced` has been removed.

### 1.0.1
- Bug fix.

### 1.0.0
- Initial release.
