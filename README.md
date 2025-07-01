# Clone Source

```bash
git clone -b sweet2-a15 https://github.com/Ghnkz/local_manifest --depth=1 .repo/local_manifests
```
# Then to sync up:
```
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags --optimized-fetch
```
