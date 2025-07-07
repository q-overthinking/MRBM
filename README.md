A simple MBR management utility written in Rust
## How to use?
```
Usage: mbrm [OPTIONS] --input <INPUT>
Options:
  -i, --input <INPUT>                  
  -c, --chunk-symbols <CHUNK_SYMBOLS>  Sets amount of symbols in one chunk [default: 16]
  -b, --blake3                         Prints blake3 MBR checksum at end of output
  -o, --output <OUTPUT>                Writes MBR data to given path
  -n, --no-color                       Removes color from MBR hex dump
  -h, --help                           Print help
  -V, --version                        Print version
```
