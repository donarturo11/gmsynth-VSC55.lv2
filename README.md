gmsynth-VSC55.lv2 - General MIDI Synth (VSC55)
================================

gmsynth-VSC55.lv2 is a General MIDI Sample Player Plugin based on VSC55 samples.

Install
-------

Compiling gmsynth requires the LV2 SDK, gnu-make, a c++-compiler.

```bash
  git clone https://github.com/donarturo11/gmsynth-VSC55.lv2.git 
  cd gmsynth-VSC55.lv2
  make
  sudo make install PREFIX=/usr
```

Note to packagers: the Makefile honors `PREFIX` and `DESTDIR` variables as well
as `CXXLAGS`, `LDFLAGS` and `OPTIMIZATIONS` (additions to `CXXFLAGS`), also
see the first 10 lines of the Makefile.
