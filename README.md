# startscript
python script to block ports, games from a list with age-restriction and option to command it remote via ssh
all code is written for debian based linux-systems

# Control Program for Computer System

This repository contains Python code for a control program used in a specialized context to control various aspects of a computer system. The program can receive commands via a socket connection from an external control program (best via ssh-snippet for now) and perform tasks such as opening and closing ports, enabling and disabling the printer, updating the system, and monitoring games.

## Features

- Command Processing: The program can handle various commands (best remote via ssh for now) such as reboot, power off, open and close ports, system updates, and more.

- Game Monitoring: The program monitors the status of games and can games can belocked or remotely unlocked, depending on the configured age restrictions. This functionality helps ensure that age-appropriate games are accessible and provides control over access to potentially restricted content. Games get back in locked state after a period of time without keyboard or mouse interaction.

- LAN Mode: unlocks ports and age-restriction at once till locked manualy or restart.

- Printer Management: The program can enable or disable the printer.

- Status Check: It can check the current system status and display whether ports are open or closed, the printer is enabled or disabled, and whether system updates are available.
