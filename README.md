# Clone Source

```bash
git clone -b lineage-22.2 https://github.com/shezan-tech/local_manifest --depth=1 .repo/local_manifests
```
# Then to sync up:
```
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags --optimized-fetch
```
