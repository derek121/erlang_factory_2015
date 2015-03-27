# Steganography and Erlang
Presentation at [Erlang Factory 2015](http://www.erlang-factory.com/sfbay2015/derek-brown) (slides to come).

## [img_stego](https://github.com/derek121/img_stego)

Embedding data in images. See the presentation slides and the repository for details.

The images and data files used in the presentation can be found in the `img_stego/` directory.

The image `innocuous.png` was created as follows:

```
1> img_png:add_message_from_file("erlang-the-movie.png", "building.png", "innocuous.png").
```

The image `all_black_300x300.png` was created with GIMP.

##[icmp_stego](https://github.com/derek121/icmp_stego)
Embedding data in ICMP Echo packets. See the presentation slides and the repository for details.

