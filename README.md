# windows-2000-disk-image
 Windows 2000 disk image ready-to-build, no Windows setup needed.

# How to build
First, use the build.EXE executable. 

Once open, click on "Unite" button to build. Once finished building, you can use Windows 2000 by using the "win2k.disk" file.

For example, with QEMU, you can use it by running:

```
qemu-system-x86_64 -m 64 -hda win2k.disk -boot c
```