# glsl-hsv2rgb [![stable](http://badges.github.io/stability-badges/dist/stable.svg)](http://github.com/badges/stability-badges)

Fast conversion from HSV color to RGB – published to npm for use with
[glslify](http://github.com/chrisdickinson/glslify), originally sourced from
[this post](http://lolengine.net/blog/2013/07/27/rgb-to-hsv-in-glsl) written
by [Sam Hocevar](http://sam.zoy.org/).

## Usage ##

[![glsl-hsv2rgb](https://nodei.co/npm/glsl-hsv2rgb.png?mini=true)](http://npmjs.org/package/glsl-hsv2rgb)

### `vec3 rgb = hsv2rgb(vec3 hsv)` ###

Takes a `vec3` where:

* `hsv.x` is the hue.
* `hsv.y` is the saturation.
* `hsv.z` is the value.

All of the values should range between 0 and 1. Returns the calculated RGB
value as a `vec3`.
