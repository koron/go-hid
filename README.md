# HIDAPI Bindings for Go

![](.github/images/gopher.png)

[![](https://travis-ci.org/sstallion/go-hid.svg?branch=master)][1]
[![](https://godoc.org/github.com/sstallion/go-hid?status.svg)][2]
[![](https://goreportcard.com/badge/github.com/sstallion/go-hid)][3]
[![](https://img.shields.io/github/license/sstallion/go-hid.svg)][4]

Package `hid` provides an idiomatic interface to HIDAPI, a simple library for
communicating with USB and Bluetooth HID devices on FreeBSD, Linux, macOS, and
Windows.

See https://github.com/signal11/hidapi for details.

## Documentation

Up-to-date documentation can be found on [GoDoc][2], or by issuing the `go doc`
command after installing the package:

    $ go doc -all github.com/sstallion/go-hid

## Installation

Package `hid` may be installed via the `go get` command:

    $ go get github.com/sstallion/go-hid@latest

>**Note**: The prerequisites for HIDAPI must be available prior to installation.
> See the HIDAPI [README][5] for details.

### lshid

An example command named `lshid` is provided, which displays information about
HID devices attached to the system. `lshid` may be installed by issuing:

    $ go get github.com/sstallion/go-hid/cmd/lshid@latest

Once installed, issue `lshid -h` to display usage.

## Contributing

Pull requests are welcome! See [CONTRIBUTING.md][6] for more details.

## License

Source code in this repository is licensed under a Simplified BSD License. See
[LICENSE][6] for more details.

[1]: https://travis-ci.org/sstallion/go-hid
[2]: https://godoc.org/github.com/sstallion/go-hid
[3]: https://goreportcard.com/report/github.com/sstallion/go-hid
[4]: https://github.com/sstallion/go-hid/blob/master/LICENSE
[5]: https://github.com/signal11/hidapi/blob/master/README.txt
[6]: https://github.com/sstallion/go-hid/blob/master/CONTRIBUTING.md
