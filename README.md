fmemopen is missing
downloaded from http://jverkoey.github.io/fmemopen/
but open_memstream is missing. therefore add

#undef HAVE_FMEMOPEN
 
in jpegio.c
pngio.c
bmpio.c
pnmio.c

of Leptonica

