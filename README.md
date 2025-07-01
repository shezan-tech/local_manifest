# Clone Source

```bash
git clone https://github.com/Ghnkz/local_manifest --depth=1 .repo/local_manifests
```
# Then to sync up:
```
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags --optimized-fetch
```
