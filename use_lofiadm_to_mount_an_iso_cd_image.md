# Use lofiadm to Mount an ISO CD image

## Mount ISO image
```
# lofiadm -a /path/to/file.iso /dev/lofi/1
```

```
# mount -F hsfs /dev/lofi/1 /mnt
```

## Unmount ISO image
```
# umount /mnt
```

```
# lofiadm -d /dev/lofi/1
```
