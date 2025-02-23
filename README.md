# Zram Lz4 Enable

The purpose of this module is to change the compression algorithm from zram to lz4

This can bring a considerable improvement to weak cell phones

# compatibility

Use this command to check the availability of the Lz4 algorithm in your kernel:

cat /sys/block/zram0/comp_algorithm

Enter this command in termux to find out if the lz4 compression algorithm is available in your kernel.
