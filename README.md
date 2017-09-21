# multibase
Utility for multi base encoding and decoding

Bored of using multiples tools for base encoding?
Multibase is a tool written in Go that allows you to encode/decode strings and files in differents base


Supported encoding and decoding methods:

- [x] base32
- [x] base58
- [x] base64

## Usage

```
Usage:
  multibase | mb [OPTIONS]

Application Options:
      --b32      Generate base32 of given string/file
      --b58      Generate base58 of given string/file
      --b64      Generate base64 of given string/file
  -d, --decode   Decode data
  -v, --version  Print version

Help Options:
  -h, --help     Show this help message
```
## Installation

- Solving dependencies
```
$ go get -v "github.com/jbenet/go-base58"
$ go get -v "github.com/jessevdk/go-flags"
```
- Cloning and building
`$ git clone https://github.com/Nhoya/multibase && cd multibase`
`$ go build`

- Installing
`# mv multibase /usr/local/bin/mb
```
