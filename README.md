![banner](https://raw.githubusercontent.com/xdroid-oss/.github/55654e4a1b88977f60e2116d7cbeed17e87f450b/banner.png)
# xdroidOSS | Local manifest for Redmi Note 10

### Sync our source ###
```bash
repo init -u https://github.com/xdroid-oss/xd_manifest -b fourteen --git-lfs
```
```bash
git clone https://github.com/Waxaranai/local_manifests -b fourteen-rn10 .repo/local_manifests
```
```bash
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

![footer](https://github.com/xdroid-oss/.github/raw/main/footer.png)
