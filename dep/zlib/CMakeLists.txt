set(zlib_SRC
adler32.c
compress.c
crc32.c
deflate.c
gzio.c
infback.c
inffast.c
inflate.c
inftrees.c
trees.c
uncompr.c
zutil.c
)

add_library(zlib ${zlib_SRC})