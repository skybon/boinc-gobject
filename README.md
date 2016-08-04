# boinc-rpc-gobject
GObject-based RPC API for BOINC client.

## Dependencies
* Vala (version 0.32.0 or later)
* Glib
* GIO
* GXml (version 0.10.0 or later)

## Installation
```
autoreconf --install
./configure --prefix=/usr
make
make DESTDIR=/usr install
```

## License
This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Lesser General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU Lesser General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
