FS-$(CONFIG_FS_EXT4)		+= ext4/
FS-$(CONFIG_FS_EXT2)		+= ext2/
FS-$(CONFIG_FS_MINIX)		+= minix/
FS-$(CONFIG_FS_MSDOS)		+= msdos/
FS-$(CONFIG_FS_XV6)		+= xv6/
FS-$(CONFIG_FS_APOLLO)		+= Apollo/
FS-$(CONFIG_FS_DEBIAN_LEGACY)	+= Debian/

FS_MAKEDIR := $(patsubst %/, $(srctree)/fs/%/Makefile, $(FS-y))

include $(FS_MAKEDIR)
