# Chalmers Unsupported Software

## Current software
There is a collection of both useful and less useful software currently installed.
There are also some useful libraries installed.

### Useful (click the names to read more)
* [i3wm 4.16.1](./software/i3) (read how to use [here](./software/i3/README.md))
* [wine 4.0](./software/wine)
* More installed and are in progress of being listed here...

### Less useful (click the names to read more)
* [lolcat 99.9.20](./software/lolcat)
* More installed and are in progress of being listed here...

### Libraries (probably used by above software) (click the names to read more)
* Coming...

## How to use the softwares in unsup?
1. Create the file `~/.vcs4/pathsetup` with the content `unsup`
2. Logout
3. Login
4. Profit

## How to build them yourself?
Look in the `install.log` files for each software. You can run `awk '/^--BEGIN MAKEFILE--$/{flag=1;next}/^--END MAKEFILE--$/{flag=0}flag' install.log > Makefile` to get a `Makefile`.

## Need more software?
Create an issue and I can see what I can do. Better yet, issue a pull request!

## Author
Emil Hemdal

## License
AGPLv3 (see LICENSE.md)

