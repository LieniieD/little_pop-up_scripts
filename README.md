# little_pop-up_scripts

## Windows client

- Add-Type -AssemblyName PresentationFramework
[System.Windows.MessageBox]::Show("You CONNECT", "Warning!")

- Add-Type -AssemblyName PresentationFramework
[System.Windows.MessageBox]::Show("You DISCONNECT", "Warning!")

## Linux client

- #!/bin/bash
zenity --warning --text "CONNECT" &

- #!/bin/bash
zenity --warning --text "DISCONNECT" &

## MacOS client

- osascript -e 'display dialog "CONNECT" with title "Warning!" buttons {"OK"} default button "OK"'

- osascript -e 'display dialog "DISCONNECT" with title "Warning!" buttons {"OK"} default button "OK"'
