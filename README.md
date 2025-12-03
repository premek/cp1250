# Gleam Windows-1250 (cp1250) Decoder

[![Package Version](https://img.shields.io/hexpm/v/cp1250)](https://hex.pm/packages/cp1250)
[![Hex Docs](https://img.shields.io/badge/hex-docs-ffaff3)](https://hexdocs.pm/cp1250/)

Thanks to https://github.com/richard-viney/iso_8859

```sh
gleam add cp1250
```
```gleam
import cp1250

pub fn main() -> Nil {
  let bytes = <<0x8E, 0xF9, 0x9E, 0x6F>>
  echo cp1250.decode(bytes)
}
```

## Development

```sh
gleam run   # Run the project
gleam test  # Run the tests
```

## License

This library is published under the MIT license, a copy of which is included.
