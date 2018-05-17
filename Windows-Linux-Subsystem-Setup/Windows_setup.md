## In order to set up a Windows computer, we'll have to download a few things for windows.

1. [Atom](https://atom.io/) - Your text editor
2. [Google Chrome](https://www.google.com/chrome/) - Get the Chrome web browser if you don't already
1. [Postgresql](https://www.openscg.com/bigsql/postgresql/installers.jsp/) - Get the stable version
    1. to setup the user, type this in powershell: `createuser -U postgres -dS "$(wsl whoami)"`
    2. you may need to create the db for the user too: `createdb -U $(wsl whoami) "$(wsl whoami)"`
4. Windows 10, version 1803 now has a shared environment variable: `WSLENV`. This means we can automate some more things!
    1. For example, we can create an alias to send us home in case we get out of our windows path inside of `bash`.
