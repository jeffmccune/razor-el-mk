Files in this directory ending in `.patch` will be applied to the initial ram
disk.  This provides an opportunity to patch the behavior of dracut, which is
necessary for bugs like the one fixed at
http://git.kernel.org/cgit/boot/dracut/dracut.git/commit/?id=ba9368fa4fedda0f72d84f910d01d7da201405a3
but which are not available in the OS packages yet.
