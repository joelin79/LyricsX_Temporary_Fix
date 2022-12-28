# LyricsX_Temporary_Fix
An AppleScript that restarts LyricsX whenever song changes. LyricsX will then be able to fetch the lyrics of each songs.

## Download

Download "LyricsX_Temporary_Fix.scpt"

## Execution
Right click the folder where you store the file select "New Terminal at Folder".

### In the terminal:
  
##### To Activate script:
  
```
nohup osascript LyricsX_Temporary_Fix.scpt &
```
        
Runs the AppleScript in the background

Note: The script will restart LyricsX without changing windows focus.
        
##### To Terminate script:
      
```
pkill -f "LyricsX_Temporary_Fix"
```
Terminates the AppleScript

Do this is anything goes wrong. 
