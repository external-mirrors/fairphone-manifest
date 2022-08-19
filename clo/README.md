# CLO manifests

Manifests here are based on [codelinaro](https://www.codelinaro.org/projects/clo/la)
manifests. Once added, manifests have been re-organised to mirror the pattern found in AOSP
manifests. I.e path, name, groups, clone-depth, revision.

E.g.
`<project path="prebuilts/deqp" name="platform/prebuilts/deqp" groups="pdk-fs" clone-depth="1" revision="ks-aosp.lnx.1.0.r4-rel" />`

## Obtaining manifests
Manifests can be found with:
```bash
$ repo init -u https://git.codelinaro.org/clo/la/platform/manifest
$ cd .repo/manifests
$ git checkout release
```
All released manifests should now be visible.
