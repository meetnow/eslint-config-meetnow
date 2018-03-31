# eslint-config-meetnow

This package provides MeetNow's .eslintrc as an extensible shared config.

Most parts of this package are inspired by Airbnb's configuration.

## Usage

1. Install the correct versions of each package, which are listed by the command:

  ```sh
  npm info "eslint-config-meetnow@latest" peerDependencies
  ```

  This can be done manually or by using [install-peerdeps](https://github.com/nathanhleung/install-peerdeps).

  ```sh
  npm install -g install-peerdeps
  install-peerdeps --dev eslint-config-meetnow
  ```

2. Add `"extends": "meetnow"` to your .eslintrc
