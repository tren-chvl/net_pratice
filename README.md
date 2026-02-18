_This project has been created as part of the 42 curriculum by marcheva._
NetPractice
Description

NetPractice is a training project designed to introduce the basics of computer networking.
Through 10 levels, you configure small simulated networks by assigning IP addresses, subnet masks, and gateways to make each network fully functional.
The goal is to understand essential networking concepts such as IP addressing, subnetting, routing, and the role of gateways and routers.
Instructions
How to run the training interface

    Download the archive provided on the project page.

    Extract the files into any folder.

    Inside this folder, run:

Code

./run.sh

This script launches a local web server and automatically opens the interface in your browser.
If the script does not work, you can manually start the server:
Code

python3 -m http.server 49242

Then open your browser at:
Code

http://localhost:49242

How to use the interface

    Enter your 42 login (marcheva) in the login field.

    Solve each level by configuring the unshaded fields (IP, mask, gateway, router interfaces, etc.).

    Use Check again to validate your configuration.

    When the level is correct, click Get my config to export your configuration file.

Submission requirements

At the root of your Git repository, you must include:

    10 configuration files (one per level), exported using Get my config.

    README.md (this file).

    The project files, including run.sh, so the interface can be launched.

Your repository must contain exactly:
Code

level1.txt
level2.txt
level3.txt
level4.txt
level5.txt
level6.txt
level7.txt
level8.txt
level9.txt
level10.txt

Resources
Networking concepts involved

    TCP/IP addressing

    Subnet masks

    Default gateways

    Routers and routing

    Switches

    OSI model (basic understanding)

    IP connectivity and reachability

    Local vs remote networks

Documentation & references

    RFC 791 — Internet Protocol

    RFC 950 — Subnetting

    Basic networking tutorials

    Subnetting explanations (for learning only, not allowed during evaluation)

Use of AI

AI was used only for:

    Summarizing project instructions

    Writing this README

    Clarifying networking concepts during training

All configurations were understood and validated manually.
Author

marcheva — 42 Le Havre
