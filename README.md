heroku-buildpack-vips
=====================

Heroku buildpack with [libvips](https://github.com/libvips/libvips) installed.


## Usage

Add this buildpack to your app:

```
https://github.com/machinio/heroku-buildpack-vips
```

## Build script

[This](./build.sh) is the script used to build vips using docker.

```sh
./build.sh
```

After building a tar file, it will be copied to the `build` directory. Then you should commit this changes to git.
