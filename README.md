# tesla_models

FiveM Tesla Model S with custom handling

## Requirements
None

## tesla_models

- Tesla Model S
    - Custom handling, mimicking real-life expectations
    - Best in class acceleration: 0-60 ~4sec, 0-100 ~7sec
    - Limited top end due to increased drag: ~160mph
    - Better than average handling
    - Low center of gravity, limited roll-over

## Download & Installation

This resource was developed alongside [tesla_ev], [tesla_supercharger]. This resource works without them, but you might be interested in installing them altogether.

### Using Git
```
cd resources
git clone https://github.com/boostvolt/tesla_models [tesla]/tesla_models/

git clone https://github.com/boostvolt/tesla_ev [tesla]/tesla_ev/
git clone https://github.com/boostvolt/tesla_supercharger [tesla]/tesla_supercharger/
```

### Manually
- Download https://github.com/boostvolt/tesla_models/archive/master.zip
- Create and place in in `[tesla]/tesla_models` directory

## Installation
- Add this in your `server.cfg`:

```lua
start tesla_models
-- if you downloaded related resources
start tesla_ev
start tesla_supercharger
```

## Screenshots

![1](https://github.com/Boostvolt/tesla_models/blob/master/img/ModelS_1.jpg)

![2](https://github.com/Boostvolt/tesla_models/blob/master/img/ModelS_2.jpg)


[wtf_ev]: https://github.com/boostvolt/tesla_ev
[wtf_tesla_supercharger]: https://github.com/boostvolt/tesla_supercharger

## License

If you distribute a copy or make a fork of the project, you have to credit this project as source.

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program.  If not, see http://www.gnu.org/licenses/.
