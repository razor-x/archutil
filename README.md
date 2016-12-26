# archutil

[![Release](https://img.shields.io/github/release/razor-x/archutil.svg)](https://github.com/razor-x/archutil/releases)
[![MIT License](https://img.shields.io/github/license/razor-x/archutil.svg)](./LICENSE.txt)

Please see the upstream project for the original
[README](https://github.com/gsingh93/archutil).

## Description

This fork has been updated for Python 3,
and modified to use a `yaml` configuration file: `archutil.yml`.
The configuration management functions have been removed.

The location of `archutil.yml` can be specified via the `-c` flag.
By default, `archutil` will look for this file in the following order:

1. In the current working directory.
2. In `/usr/local/etc`.

Addtional changes include a new `--sets` flags and better AUR support.

## Installation

Only `bin/archutil` is required.
This can be installed manually to `/usr/local/bin`.

You will also need the `python` and `python-yaml` packages.

For convenience, the latest version of `archutil` is provided at
https://io.evansosenko.com/archutil/archutil
and a `package.json` is included for use with npm or yarn.

For fetching and installing during initial setup, you can use

```bash
$ [sudo] curl -L -o /usr/local/bin/archutil https://git.io/jgz3
$ [sudo] chmod +x /usr/local/bin/archutil
```

## Contributing

Please submit and comment on bug reports and feature requests.

To submit a patch:

1. Fork it (https://github.com/razor-x/vimrc/fork).
2. Create your feature branch (`git checkout -b my-new-feature`).
3. Make changes.
4. Commit your changes (`git commit -am 'Add some feature'`).
5. Push to the branch (`git push origin my-new-feature`).
6. Create a new Pull Request.

## License

archutil is licensed under the MIT license.

## Warranty

This software is provided "as is" and without any express or
implied warranties, including, without limitation, the implied
warranties of merchantibility and fitness for a particular
purpose.
