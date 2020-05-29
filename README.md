# i3-gaps wit feature 262

this branch allow to setting negative gap with a 'set' command [#262](https://github.com/Airblader/i3/issues/262)

**NOTE:** feature was [merged](https://github.com/Airblader/i3/commit/b394bc3e339092d4b1e0dc578d9a4e94080d85ba) into i3-gaps master branch.  

## Build & Install
```bash
autoreconf -fi
mkdir -p build && cd build
../configure
make -j16
sudo make install
```
