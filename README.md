# cros-fw-pack
Minimal tools to pack image

1/ copy generated coreboot.rom depthcharge.elf  ec.RW.bin  ec.RW.flat into build dir

2/ run ./build_image.sh to pack

$ ./build_image.sh

Building image ./image.dev.bin

3/ run ./set_gbb_flags.sh to set gbb flags

$ ./set_gbb_flags.sh -f image.dev.bin 0x239

Setting GBB flags from flags: 0x00004039 to 0x239..successfully saved new image to: image.dev.bin
