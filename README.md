# ShareLock Keypad

Web Bluetooth keypad demo for the ShareLock WB55 lock board. Open the site in Chrome on Android, tap Connect and
pick the lock (`SLOCK-XXXX`). Each key is sent to the lock as you press it, and the indicator shows whether it's
locked or unlocked. "Add to Home screen" installs it as an app.

The source of truth is `Tools/ble_keypad/web` in the sharelock-firmware repository; this repo only hosts it.
