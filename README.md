# Geran-4

[![CI](https://github.com/Sam-DarkBall-Mods/Geran-4/actions/workflows/ci.yml/badge.svg)](https://github.com/Sam-DarkBall-Mods/Geran-4/actions/workflows/ci.yml)

Geran-4 is a turbojet attack UAV for Arma 3. The mod includes versions for all
three sides, tripod launchers, an ammunition box and the scripts used for
guidance and target selection.

## Requirements

- Arma 3 2.22 or newer
- CBA_A3

## Building

```bash
python3 -B -m unittest discover -s tests -p "test_*.py" -v
hemtt check
hemtt build --no-bin
```

The source now uses a normal HEMTT layout, but the PBO is still named
`geran4.pbo` and keeps the `geran4` virtual prefix.

## License

Code and configs use GPL-2.0-or-later. Original game assets use APL-SA. See
[LICENSES.md](LICENSES.md).
