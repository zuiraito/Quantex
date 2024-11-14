# Kaltext
A terminal application to manage events and scedjule (German).

# Usage
| Command | |
| -- | |
|t| display open tasks with corresponding week number|
|tag |display plans for the day |
|woche |display plans for the week |
|wochen {number} |display plans for the following weeks |
|termin {dd}.{mm}.{yy} | add an appointment |

# Installation
```
git clone https://github.com/zuiraito/Kaltext
```
To make the commands executable from any directory in the terminal, some lines need to be added to the bash.rc
```
cat Kaltext/addToBashRC >> ~/.bash.rc
```
If the Kaltext directory is not in the ~/ directory, the "kalender_path" variable in the bash.rc has to be changed.

# Syncing
The ~/Kaltext directory can be synced to other devices using [syncthing](https://github.com/syncthing/syncthing) to other devices and even moblie when running a terminal emulator like terminux.
