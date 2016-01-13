Build on MINGW (with dump_syms)
===============================

```
autoreconf
CPPFLAGS=-D__USE_MINGW_ANSI_STDIO LIBS=-lws2_32 ./configure && make
```

