## StreamController and Timers
Timers are used for pre-game countdowns as well as downtime between sets or game changes.
You can use this timer forever you may need. You only need the files in the folder in order for this to work.

## Folder Breakdown
  ps don't rename any of these folders or files if you don't know what you're doing.
1. js - javascript libraries linked to the `html` files. don't touch these files.
2. overlays - where the html files live for design purposes of your overlays
3. sc - `StreamController` central. magic and settings for stream controller.
4. Timer.md - READ ME.


## StreamController Extra Documentation [v 1.0.0 - 5/12/2020]
For items not documented on the website. This relates only to the `timers` and their components.

`timestamp` - Timestamp is an attibute for the `StreamController` Application's `Button` tag. This allows for streamers to set up a timer.  Requires you to have a `ComboBox` with
the ID of `timerLength` in order to function properly. By default, once the timer
is finished, `NOW!` will appear in replacement of the timer. I am working on making this
editable.
The `checkbox` that is "connected" to the `timestamp` `Button` must have an `id` of `timerEnable` in order to be properly functional (i.e. to be active on load, should you set it). It also will not properly hide/show the timer upon clicking the `timestamp` `Button` unless this had been named properly.
`To Implement:` Error checking for button naming conventions. Default to normal load / show error box on how to fix the said error.
