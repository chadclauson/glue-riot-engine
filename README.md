# glue-riot-engine

Pinned engine packs that the Glue desktop app downloads on first use. Each release holds one zip;
the app checks its exact size and sha256 before installing it.

## riot-engine-1

`riot-engine-1.zip` (1,036,431,802 bytes, sha256 `944b1a0ff39330163fd3e7a0b0eeeb7162b70afd3a5a3e7d74de17fd0d0cc9a7`)

| Path | Contents | Source and license |
|---|---|---|
| `browser/` | Camoufox 156.0.1-beta.38 for Windows x86_64, unmodified, with `fonts/` reduced to the macOS font families | [daijro/camoufox](https://github.com/daijro/camoufox) release `v156.0.1-beta.38`; Mozilla Public License 2.0 (Firefox) and the licenses listed in the build |
| `data/camoufox/camoufox/Cache/addons/UBO/` | uBlock Origin 1.75.0, unmodified | [gorhill/uBlock](https://github.com/gorhill/uBlock); GPL-3.0 |
| `data/camoufox/camoufox/Cache/geoip/` | "GeoIP AIO" combined IPv4/IPv6 database | [daijro/geoip-all-in-one](https://github.com/daijro/geoip-all-in-one); see that repository for the licenses and attribution of the databases it merges |
| `data/camoufox/camoufox/Cache/fpgen/` | Fingerprint model pinned by `@camoufox/camoufox` 0.5.7 | [scrapfly/fingerprint-generator](https://github.com/scrapfly/fingerprint-generator) via Camoufox; see upstream for its license |
| `engine.json` | Versions of the above | — |

All components are redistributed unmodified (apart from the font subset). Source code for the
GPL and MPL components is available from the upstream projects linked above.
