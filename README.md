> [!WARNING]
> This Project is archived, even thought it never got a working build i am still not continuing this because it was a one-off inside joke that died after a week or two

<div align="center">
<a href="https://github.com/Djihads1/FreakPatch/releases/latest"><img src="https://images.weserv.nl/?url=https://raw.githubusercontent.com/Djihads1/FreakPatch/main/app/src/main/res/mipmap-xxxhdpi/ic_launcher.png&mask=circle" style="width: 128px;" alt="logo"></a>

<h1 align="center">FreakPatch</h1>

[![Latest Release](https://img.shields.io/github/v/release/bmax121/APatch?label=Release&logo=github)](https://github.com/Djihads1/FreakPatch/releases/latest)
[![Channel](https://img.shields.io/badge/Follow-Telegram-blue.svg?logo=telegram)](https://t.me/APatchGroup)
[![GitHub License](https://img.shields.io/github/license/bmax121/APatch?logo=gnu)](/LICENSE)

</div>

The patching of Android kernel and Android system, but its 𝓯𝓻𝓮𝓪𝓴𝔂.

- A 𝓯𝓻𝓮𝓪𝓴𝔂 kernel-based root solution for Android devices.
- APM: Support for modules similar to Magisk.
- KPM: Support for modules that allow you to inject any code into the kernel (Requires kernel function `inline-hook` and `syscall-table-hook` enabled).
- FreakPatch relies on [KernelPatch](https://github.com/bmax121/KernelPatch/).
- The FreakPatch UI and the APModule source code have been derived and modified from [KernelSU](https://github.com/tiann/KernelSU).

## Why

<a href="https://www.youtube.com/watch?v=z6bC9QtgMtk"><img src="https://i.imgur.com/6TnfKwF.png" style="width: 250px;" alt="freakbob"></a>

## Supported Versions

- Only supports the ARM64 architecture.
- Only supports Android kernel versions 3.18 - 6.1

Support for Samsung devices with security protection: Planned

## Requirement

Kernel configs:

- `CONFIG_KALLSYMS=y` and `CONFIG_KALLSYMS_ALL=y`

- `CONFIG_KALLSYMS=y` and `CONFIG_KALLSYMS_ALL=n`: Initial support

## Security Alert

The **SuperKey** has higher privileges than root access.  
Weak or compromised keys can lead to unauthorized control of your device.  
It is critical to use robust keys and safeguard them from exposure to maintain the security of your device.

## Get Help

### Usage

For usage, please refer to [the APatch official documentation](https://apatch.dev).  
It's worth noting that the documentation is currently not quite complete, and the content may change at any time.  


## Credits

- [KernelPatch](https://github.com/bmax121/KernelPatch/): The core.
- [Magisk](https://github.com/topjohnwu/Magisk): magiskboot and magiskpolicy.
- [KernelSU](https://github.com/tiann/KernelSU): App UI, and Magisk module like support.
- [APatch](https://github.com/bmax121/APatch): Android Patch

## License

FreakPatch is licensed under the GNU General Public License v3 [GPL-3](http://www.gnu.org/copyleft/gpl.html).
