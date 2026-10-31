# Unison releases

Downloads for Unison, a native Discord client. Get the latest build at https://unison.woflydev.com

## Source

The engine source is open. Each release ships it in the devkit, `unison-devkit-<version>.zip`: the Rust engine, generated bindings, prebuilt libraries and a `START_HERE.md` for building a shell on top of it. Take the devkit from the release that matches the app version you run.

## License

GNU General Public License, version 3 or (at your option) any later version (GPL-3.0-or-later). The license text is in `LICENSE` inside every devkit.

## Verifying a download

Each release includes `SHA256SUMS`. Check with `shasum -a 256 -c SHA256SUMS`.
