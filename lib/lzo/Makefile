lzo_compress-objs := lzo1x_compress.o
lzo_decompress-objs := lzo1x_decompress_safe.o

obj-$(CONFIG_LZO_COMPRESS) += lzo_compress.o
obj-$(CONFIG_LZO_DECOMPRESS) += lzo_decompress.o

# Squeeze a little bit more juice
ccflags-y := -O3
ccflags-y += $(call cc-option, -g0)
ccflags-y += $(call cc-option, -Os)
