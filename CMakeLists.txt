set(lzma_SOURCES
  7zTypes.h
  Lzma2Dec.h
  Lzma2Dec.c
  LzmaDec.h
  LzmaDec.c
  Precomp.h)

add_library(lzma STATIC ${lzma_SOURCES})
