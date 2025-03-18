Backdoor Development
This repository contains the development of a backdoor tool written in Python disguised as a Snake game.

Table of Contents
Introduction
Features
Installation
Usage
Contributing
License
Introduction
The Backdoor Development project aims to create a secure and efficient backdoor tool for penetration testing purposes. This tool is designed for ethical hacking and cybersecurity professionals to test the security of their systems. It is disguised as a Snake game to facilitate its deployment.

Features
Remote access to target machines
Persistence mechanisms
Disguised as a Snake game
Cleanup application to remove persistence
Installation
To install the backdoor tool, follow these steps:

Clone the repository:
git clone https://github.com/Viateur-akimana/Backdoor-development.git
Navigate to the project directory:
cd Backdoor-development
Install the required dependencies:
pipenv install
Usage
To use the backdoor tool

Running the Game
Run the game:
python game.py
The game will check for required apps and install them if needed.
The game will establish persistence on the target system.
The game will open a reverse TCP shell to the specified host and port.
Cleanup
To remove the persistence and terminate the game, run the cleanup script:
python cleanup.py
Contributing
Contributions are welcome!