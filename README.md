# Steganography and Erlang
Presentation at [Erlang Factory 2015](http://www.erlang-factory.com/sfbay2015/derek-brown).

## [img_stego](https://github.com/derek121/img_stego)

Embedding data in images. See the presentation slides (to come) and the repository for details.

The image `innocuous.png` used in the presentation was created as follows, using source files found in the `img_stego/` directory here:

```
1> img_png:add_message_from_file("erlang-the-movie.png", "building.png", "innocuous.png").
```

The image `all_black_300x300.png` in the presentation is also in `img_stego/`.