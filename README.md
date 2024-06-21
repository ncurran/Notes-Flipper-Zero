# Notes-Flipper-Zero
## Side-Loading Applications
- You can install a single application without building/flashing the entire firmware and without going through any app store
### Install ubft
- with `pip3 install --user ufbt`
### Download the app
- eg, such as the awesome Boilerplate app from leedave
- with `git clone https://github.com/leedave/flipper-zero-fap-boilerplate`
- mkae sure to `cd flipper-zero-fap-boilerplate`
### Or create it
- `mkdir my app`
- `cd myapp`
- ` ufbt create APPID=myapp`
### Build the app
- `ufbt`
