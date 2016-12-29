include $(top_srcdir)/common.mk

bin_PROGRAMS = template11.elf
template11_elf_CFLAGS=$(AM_CFLAGS) $(C11FLAGS) -T$(srcdir)/linker.ld -marm #-nostartfiles
#payload_stage1_elf_CCASFLAGS = -I$(top_srcdir)/data
template11_elf_SOURCES = src/main.c src/crt0.s

EXTRA_DIST=linker.ld

