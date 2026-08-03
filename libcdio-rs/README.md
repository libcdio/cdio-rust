# libcdio-rs
Safe Rust abstraction over libcdio C.
To use the raw FFI bindings, check out [libcdio-sys](https://crates.io/crates/libcdio-sys).

## SCSI MMC spec references
This library is primarily based on SCSI's [MMC-6][1] and [SPC-3][2].

However, in an attempt to achieve feature parity with libcdio C, a few
commands and options of existing commands that are marked legacy in
MMC-6 have also been implemented.
See Annexure E on legacy specifications in MMC-6 to find the last
supported MMC version for said command or option.

[1]: https://www.13thmonkey.org/documentation/SCSI/mmc6r02g.pdf
[2]: https://www.13thmonkey.org/documentation/SCSI/spc3r23.pdf

## License
Copyright (C) 2026 Shiva Kiran Koninty <shiva@skran.xyz>

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by the
Free Software Foundation, either version 3 of the License, or (at your
option) any later version.

This program is distributed in the hope that it will be useful, but
WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU
General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program. If not, see <https://www.gnu.org/licenses/>.
