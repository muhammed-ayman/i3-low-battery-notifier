# i3-low-battery-notifier
Script that warns [i3wm](http://i3wm.org/) users when the battery is low.

# Mechanism
The script checks the battery percentage & status on a regular basis and determines whether to send a notification through `notify-send` when the battery is low.

# How to use?

- Clone the script and add it to your `PATH Variable`
- Call it with your own customization in the i3wm config: `exec --no-startup-id i3-low-battery-notifier`

## Options

- `-h` : Displays the help info.

- `-T` : sets the battery percentage at which the first notification is sent. Default: `20%`

- `-t` : sets the battery percentage at which the second notification is sent. Default: `10%`

- `-i` : sets the notification icon.