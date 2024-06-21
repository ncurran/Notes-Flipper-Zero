-# Notes-Flipper-Zero
## Side-Loading Applications
- You can install a single application without building/flashing the entire firmware and without going through any app store
### Install ubft
- with `$ pip3 install --user ufbt`
### Download the app
- eg, the awesome Boilerplate app from leedave
  - with `$ git clone https://github.com/leedave/flipper-zero-fap-boilerplate`
  - and `$ cd flipper-zero-fap-boilerplate`
### Or create it
- `$ mkdir my app`
- `$ cd myapp`
- `$ ufbt create APPID=myapp`
### Build the app
- `$ ufbt`
### Install the app
- ufbt creates the dist/ subdirectory which will contain your .fap file
  - `$ cd dist`
- copy the file to the appropriate location on the device
  - this was in `SD Card/apps/` for me using Momentum firmware, I put my app in the `Tools/` subdirectory 
