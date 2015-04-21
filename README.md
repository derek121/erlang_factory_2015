# Steganography and Erlang
Presentation at [Erlang Factory 2015](http://www.erlang-factory.com/sfbay2015/derek-brown) and the [Erlang NYC Meetup](http://www.meetup.com/Erlang-NYC/events/221649711/).

##Slides
[Slides](https://github.com/derek121/erlang_factory_2015/blob/master/derek-brown-steganography-erlang.pdf)

##img_stego
[Repository](https://github.com/derek121/img_stego)

Embedding data in images. See the presentation slides and the repository for details.

The images and data files used in the presentation can be found in the `img_stego/` directory.

The image `innocuous.png` was created as follows:

```
1> img_png:add_message_from_file("erlang-the-movie.png", "building.png", "innocuous.png").
```

The image `all_black_300x300.png` was created with GIMP.

##icmp_stego
[Repository](https://github.com/derek121/icmp_stego)

Embedding data in ICMP Echo packets. See the presentation slides and the repository for details.

