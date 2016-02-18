# CM for Meizu MX4

This is the local manifest for building; just clone into `.repo/local_manifests`
and you should be all set.

```sh
# compiling for Ubuntu edition
lunch cm_arale-userdebug

# or ordinary versions of MX4 as well!
# (be sure to unlock your bootloader first, booting with stock boot.img
# is no longer supported)
lunch cm_mx4-userdebug
```


repo init cm项目后,在repo sync之前将此项目下的文件clone到预放置CM的目录的.repo目录的local_manifests下然后repo sync即可
