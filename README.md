# trash

trash is a tui fronted for [Transmission](https://transmissionbt.com/), written in bash. More precisely, it is a client for the program 'transmission-daemon'.

trash communicates with the daemon through transmission-remote. These can be installed on most Linux distributions with a package, called 'transmission-cli'.

This project was inpired by [torque](https://github.com/dylanaraps/torque/blob/master/README.md). I extended it's feature set and changed how it queries information from transmission-daemon to be able to display more info about a torrent (for example availability, seed ratio, etc).

## Dependencies

* bash
* transmission-cli

## Usage

Just run trash. You can lauch transmission-daemon by pressing the 'l' key. You can also terminate it by pressing 't'. All keybindings will be listed at the bottom while trash is running.
