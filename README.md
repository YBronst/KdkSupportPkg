# KdkSupportPkg

Repository dedicated to Kernel Debug Kit archival, with a primary focus on macOS Ventura KDKs in relation to Root Volume Patching with OpenCore Legacy Patcher.

----------

With macOS 13, Ventura, Apple dropped on-disk kernel binaries in `/System/Library/Extensions`. Due to this, end users cannot build Boot and System Kernel Collections without manually installing a Kernel Debug Kit from Apple's Developer Site. However, due to Apple's account requirement for downloads, automated retrieval is not possible. Thus this repo will create a release for each KDK seeded, with the tag representing the build associated.

Source for Kernel Debug Kits:

* [Apple Developer Site: More Downloads](https://developer.apple.com/download/all/)

----------

