# budgie

**This image is a prototype and is alpha**

### [ISOs are available in the release section](https://github.com/ublue-os/budgie/releases)

[![release-please](https://github.com/ublue-os/budgie/actions/workflows/release-please.yml/badge.svg)](https://github.com/ublue-os/budgie/actions/workflows/release-please.yml)

![image](https://user-images.githubusercontent.com/1264109/233800873-08b74495-5dae-4258-8ecd-12653762a7c2.png)

To try it:

    rpm-ostree rebase ostree-unverified-registry:ghcr.io/ublue-os/budgie-main:38

or if you have an NVIDIA GPU:

    rpm-ostree rebase ostree-unverified-registry:ghcr.io/ublue-os/budgie-nvidia:38

## Caveats

- This is using the same official packages as Fedora, but is assembled differently
  - Future images will be based on the official method
  - When that happens these images will just get updated, you probably won't need to reinstall (though you will want to to use Budgie's recommended partition layout)
  - In the meantime enjoy!
- Thanks to @jerbmega for the lightdm workaround!
