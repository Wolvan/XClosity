# This project is dead

XClosity
========
A fix to Comcast's Xfinity Gateway's being open to anyone until Comcast themselves react.

## What is XClosity?
XClosity is a small NodeJS script that loads available Xfinity routers from Shodan,
then attempts to log into those and afterwards tries to close the remote management
system.

## How can I help?

### Help closing Xfinity routers
First of all, you need to install this script. To do that is quite simple, really:
1. Install [NodeJS and NPM](https://nodejs.org/)

2. Open a command prompt

3. Type `npm i xclosity`

4. Get API Key from [Shodan](https://www.shodan.io/) and add query credits to use it

5. Run XClosity with `xclosity <Shodan API Key> [Page from] [Page count]` in the command prompt

6. Let it run until it says finished!

It's that easy

### Developing XClosity
You are a developer? Your help is always appreciated!
1. Fork this repo
2. Modify your copy
3. Create a Pull Request back to this repo

## License
This software is licensed under the MIT License, see LICENSE.md.
