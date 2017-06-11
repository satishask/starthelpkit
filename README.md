# Start Helpkit
To start the helpkit app

## Installation:
starthelpkit depends on [ttab](https://www.npmjs.com/package/ttab) which has a prerequisite for installation.

**Important**: `Terminal` / `iTerm2` (`iTerm.app`) needs to be granted _access for assistive devices_ in order for `ttab` to function properly, which is a _one-time operation that requires administrative privileges_.  
If you're not prompted on first run and get an error message instead, go to `System Preferences > Security & Privacy`, tab `Privacy`, select `Accessibility`, unlock, and make sure `Terminal.app` / `iTerm.app` is in the list on the right and has a checkmark.  
For more information, see [Apple's support article on the subject](https://support.apple.com/en-us/HT202802)

```
npm install git://github.com/satishask/starthelpkit.git -g
```

## Usage:
Use the below command in the terminal to start the helpkit app
```
starthelpkit
```
This starts the
* redis
* memcache
* rails server
* sidekiq
* elasticsearch

## License

released under the [MIT license](https://spdx.org/licenses/MIT#licenseText).

## Acknowledgements

This project gratefully depends on the following open-source components, according to the terms of their respective licenses.

## npm dependencies

* [ttab](https://github.com/mklement0/ttab)
