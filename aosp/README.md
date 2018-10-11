# AOSP manifests

Manifests here are based on the [AOSP](https://source.android.com/) manifests.

## Obtaining manifests
Manifests can be found with:
```bash
$ git fetch https://android.googlesource.com/platform/manifest --no-tags refs/heads/android-12.0.0_r26
$ git show FETCH_HEAD:default.xml > aosp/android-12.0.0_r26.xml
```
