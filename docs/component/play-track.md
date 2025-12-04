# Play Track

## Requirements
- `foobar2000` `2.24` or later. 32bit and 64bit are both supported.
- `Windows 10` or later

[Download :material-download:](https://github.com/marc2k3/fb2k-graveyard/raw/refs/heads/main/foo_play_track-1.1.0.fb2k-component){ .md-button .md-button--primary }

## Usage
This adds a `Play Track` submenu to the main `Playback` menu.

From there, you can play tracks from the `1st` to the `30th`. There is a also
a command for the `Last` track.

There are also `Random` and `Focused` commands. These are specifically for
people who have `Playback follows cursor` disabled because they function on the
active playlist even when `foobar2000` is playing from another.

### Command-line support
There is also built in command line support where you can supply any valid number for
the track index. If the supplied index exceeds the track count, the last track will always be played.

!!! example
	```
	foobar2000.exe /play_track:12
	```

## Changes

### 1.1.0
- Bump minimum requirements to `foobar2000` `2.24` and `Windows 10`.
- Compiled with the latest `foobar2000` `SDK`.

### 1.0.5
- The minimum requirement is now `foobar2000` `2.1`.
- Compiled with the latest `foobar2000` `SDK`.
