midigen.lv2 - Midi Step Sequencer
=================================

midigen.lv2 is simple step sequencer for moddevices.com

Install
-------

Compiling midigen requires the LV2 SDK, bash, gnu-make, and a c-compiler.

```bash
  git clone git://github.com/x42/stepseq.lv2.git
  cd midigen.lv2
  make
  sudo make install PREFIX=/usr
```

Note to packagers: The Makefile honors `PREFIX` and `DESTDIR` variables as well
as `CFLAGS`, `LDFLAGS` and `OPTIMIZATIONS` (additions to `CFLAGS`), also
see the first 10 lines of the Makefile.
