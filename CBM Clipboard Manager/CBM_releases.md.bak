## v2.5.2
07.03.2023
1) fixed problem where an error occurs at writing the new Clipboard content into SQL database when the Clip contains a ' (single quote)

## v2.5.1
18.02.2023
1) optimized the parsing/formatting of the date for the "Save or Delete Entry" dialog

## v2.5.0
16.02.2023
1) now showing within the "Save or Delete Entry" dialog the date and time when the chosen entry was saved and the short preview of the entry

## v2.4.4
03.02.2023
1) fixed issue where the Clipboard Manager was cancelled in some situations

## v2.4.3
1) fixed issue where not coming back to Clipboard Manager after deleting an entry

## v2.4.2
02.02.2023
1) fixed issue where inserted text was cut off after a closing bracket ")"

## v2.4.1
02.02.2023
1) corrected the perform task action in the initial task to the correct task (CBM Set Up Quick Setting Tile)

## v2.4
02.02.2023
1) added a task to setup the Quick Setting Tile, also added this in to the initial task
2) long-tap the Quick Setting Tile will know instantly open the Join Bubble with the current clipboard content

## v2.3
1) added "Join Send Push --> Clipboard Bubble" when clipboard changes
Since Android 13 the Logcat Entry Event no longer works pleasant without Root or ADB Wifi, so also the automatic snyc to your devices via Join does not work. Also Join uses this clipboard monitoring which no longer works. So I included the Join Clipboard Bubble to open when the clipboard changes.
This Clipbard Manager also uses the "Clipboard Changed" Event which uses Logcat. So Root or ADB Wifi is needed!

## v2.2
1) new long-click option: "Send with Join Bubble" If Join is installed, the Join Bubble appears to send the chosen entry to your devices
2) corrected some labels

## v2.1
1) corrected an error where it was not possible to single-delete an entry from Saved Manager

## v2.0
1) changed storing entries from arrays to SQLite database
- auto delete duplicate entries
- limit logged Clipboard entries, changeable with "CBM Change Limit" task.
- Multi-Delete option
- showing only the first 100 characters in list dialogs to keep track.
2) reworked Long-Click options:
- "Paste, Add to Saved, Delete, Multi-Delete" for Clipboard Manager entries
- "Paste, Delete, Multi-Delete" for saved entries

## v1.1
1) implemented a workaround for texts with "enter"
If the copied texts contains an "enter" it was stored in the temporary Clipboard Manager but it was not possible to paste or delete it. By saving this text only the first row was saved.
Workaround: Save text with #br# instead of "enter", but the text will be pasted with "enter" again! 12) changed from AutoInput to Keyboard-Action"