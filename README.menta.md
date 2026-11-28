# pkg-caja (Menta Linux)

Debian packaging of Caja 1.29.1 (from debian-mate-team/caja on Salsa, 1.26.4-2),
modified only to build the new upstream with Wayland support (`--enable-wayland`,
gtk-layer-shell + wayland-client).

Versioning: `<upstream>-<debian rev>mentaN`, e.g. `1.29.1-1menta1`. Bump N with
`dch -i` for each Menta rebuild.

CI builds the .debs on every push to `master`. Pushing a tag `menta/<version>`
(e.g. `menta/1.29.1-1menta1`) also publishes them as a GitHub release.
