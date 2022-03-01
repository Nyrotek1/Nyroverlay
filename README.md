## Installation (OBS)

1. Download and install the [BeatSaberHTTPStatus plugin](https://github.com/opl-/beatsaber-http-status/releases)
2. Create a Browser source
3. Set the URL as `https://nyrotek1.github.io/Nyroverlay/` and the size equal to your canvas size (1280x720, etc.)
4. (Optional) For 1080p canvases, add the `scale` modifier (ex. `https://nyrotek1.github.io/Nyroverlay/?modifiers=scale`) to scale the overlay by 1.5x

## Options
Options are added to the URL query as such:

```
https://nyrotek1.github.io/Nyroverlay/?modifiers=top
```

### `ip` and `port`

Listen to events from another IP and/or port.

### `modifiers`

Multiple modifiers can be seperated with commas.

- `top`
	* Moves the overlay to the top and reverses the layout vertically
- `rtl`
	* Moves the overlay to the right and uses right-to-left text
- `scale`
	* Scales the overlay by 1.5x, for use on 1080p canvases
- `test`
	* Makes the background black, for testing purposes
