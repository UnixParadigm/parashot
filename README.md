# Parashot

### Parashot is a fast, small, featureful and efficient script that uses maim to capture screenshots.

```
parashot 1.1.0

Usage: parashot [OPTION]

Options:
	-h		Print this help message.

	-x		Copies the image to the clipboard after capture. (Requires xclip)

	-d [FORMAT]	Use custom date format for saved image name. Defaults to %Y-%m-%d_%T.
			Refer to date(1) for date format syntax.

	-b		Verboses a PC speaker beep upon screenshot.
			Beep tone determined by failure or success. (Requires beep)

	-o [DIR]	Set the output location for the screenshot. Defaults to CWD.

	-n		Display notification on completion of screenshot. (Requires libnotify)

	-c		Screenshots the current window and saves it to OUTPUT. (Requires xdotool)

Examples:
	parashot
		This would give the user a selection tool and save the screenshot to the current working directory.

	parashot -o ~/images/screenshots
		Same as the prior example and save the screenshot to '~/images/screenshots'

	parashot -cxo ~/images/screenshots
		Capture the current window, copy it into the clipboard and save the screenshot to '~/images/screenshots'

	parashot -cxbno ~/images/screenshots
		Same as the one above except with a notification and PC speaker beep on completion.
```
