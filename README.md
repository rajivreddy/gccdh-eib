# EIB configurations for Standalone provisioning

```bash
build-eib --definition-file iso-definition.yaml
Setting up Podman API listener...
Pulling selected Helm charts... 100% |████████████████████████████████████████████████████████████████████████████████████| (1/1, 44 it/min)        
Generating image customization components...
Identifier ................... [SUCCESS]
Custom Files ................. [SKIPPED]
Time ......................... [SKIPPED]
Network ...................... [SUCCESS]
Groups ....................... [SKIPPED]
Users ........................ [SUCCESS]
Proxy ........................ [SKIPPED]
Resolving package dependencies...
Rpm .......................... [SUCCESS]
Os Files ..................... [SKIPPED]
Systemd ...................... [SKIPPED]
Fips ......................... [SKIPPED]
Elemental .................... [SKIPPED]
Suma ......................... [SKIPPED]
Populating Embedded Artifact Registry... 100% |████████████████████████████████████████████████████████████████████████| (15/15, 7 it/min)          
Embedded Artifact Registry ... [SUCCESS]
Keymap ....................... [SUCCESS]
Configuring Kubernetes component...
Downloading file: k3s_installer.sh
Downloading file: k3s-airgap-images-arm64.tar.zst 100% |█████████████████████████████████████████████████████████████| (136/136 MB, 21 MB/s)        
Downloading file: k3s-arm64 100% |█████████████████████████████████████████████████████████████████████████████████████| (66/66 MB, 11 MB/s)        
Kubernetes ................... [SUCCESS]
Certificates ................. [SKIPPED]
Cleanup ...................... [SKIPPED]
Building ISO image...
Kernel Params ................ [SKIPPED]
Build complete, the image can be found at: eib-image.iso
```


**Docs:**


https://github.com/suse-edge/edge-image-builder/blob/main/docs/building-images.md