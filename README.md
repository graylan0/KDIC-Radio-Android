# MSP-Waves-App Forked from KDIC Radio

## MSP-Waves, Conveient Radio Streaming Application

MSP-Waves is a global internet radio station, you can find more out about it at minnowsupport.org or mspwaves.com

You can obtain the source with the following command:
```shell
git clone git://github.com/graylan0/KDIC-Radio-Android.git
```

If you would like to contribute, shoot us a pull request.  


## Authors and Contributors

Homebrewed by [Grinnell AppDev](http://appdev.grinnell.edu/)!

### Current Builds

- [Michael Owusu](https://github.com/mkowusu)
- [Prabir Pradhan](https://github.com/prabirmsp)

### Currently Maintained By:
- [Linh Pham](https://github.com/LinhPha)
- [Papa Kojo Ampim-Darko](https://github.com/PapaKoj)
- [Nikunj Agarwal](https://github.com/nikagarwal98)
- [Jacob Ekstrand](https://github.com/xtrajacoby)

### Previous Builds

- Patrick Triest
- Spencer Liberto
- Travis Law

## Organization

### Directory Structure

Generated with `tree -d -I build|androidTest`.
```
.
├── app
│   ├── libs
│   └── src
│       └── main
│           ├── java
│           │   └── edu
│           │       └── grinnell
│           │           └── kdic
│           └── res
│               ├── drawable
│               ├── layout
│               ├── menu
│               ├── values
│               └── values-w820dp
└── gradle
    └── wrapper
```
- `KDIC-android.php` is the PHP script used to parse the HTML table schedule data to JSON, and is hosted [here]().


## License
```
This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
```
