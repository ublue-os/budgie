# budgie

**This image is a prototype and is alpha**

[![release-please](https://github.com/ublue-os/budgie/actions/workflows/release-please.yml/badge.svg)](https://github.com/ublue-os/budgie/actions/workflows/release-please.yml)

![image](https://user-images.githubusercontent.com/1264109/233800873-08b74495-5dae-4258-8ecd-12653762a7c2.png)

To try it:

    rpm-ostree rebase ostree-unverified-registry:ghcr.io/ublue-os/budgie:38

or

    rpm-ostree rebase ostree-unverified-registry:ghcr.io/ublue-os/budgie-nvidia:38

## Caveats

Ideally this would be based off the `base` image but currently it's just adding budgie to silverblue, you need to select budgie from the GDM screen to use it, then you should be good to go. Future versions will just have budgie as the default. 
