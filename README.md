# <img src="https://github.com/darklord-end/jellogram-desktop/blob/dev/foreground.png" width="32" height="32" align="Top"> JelloGram Desktop – Fork of official Telegram Desktop for Jellogram servers

![Version](https://img.shields.io/badge/version-latest-blue?style=flat-square&label=version&logo=telegram)
[![Build Status Windows](https://github.com/darklord-end/jellogram-desktop/actions/workflows/windows.yml/badge.svg)](https://github.com/darklord-end/jellogram-desktop/actions/workflows/windows.yml)
[![Build Status macOS](https://github.com/darklord-end/jellogram-desktop/actions/workflows/macos.yml/badge.svg)](https://github.com/darklord-end/jellogram-desktop/actions/workflows/macos.yml)
[![Build Status Linux](https://github.com/darklord-end/jellogram-desktop/actions/workflows/linux.yml/badge.svg)](https://github.com/darklord-end/jellogram-desktop/actions/workflows/linux.yml)

<p align="center">
  <img src="https://github.com/darklord-end/jellogram-desktop/blob/dev/Icon.png" width="200" alt="JelloGram Logo">
</p>

This is the complete source code and the build instructions for the official [Telegram][telegram] messenger desktop client, based on the [Telegram API][telegram_api] and the [MTProto][telegram_proto] secure protocol.

The source code is published under GPLv3 with OpenSSL exception, the license is available [here][license].

## About JelloGram

JelloGram is a community-driven fork of Telegram Desktop, adapted for use with Jellogram servers. It retains all the core features of the original client while providing compatibility with custom server endpoints.

## Version

The current version is defined in the [`Telegram/build/version`](https://github.com/darklord-end/jellogram-desktop/blob/dev/Telegram/build/version) file.  
This repository tracks the latest stable release; check the file for the exact version number.

## Resources

- [Source Code](https://github.com/darklord-end/jellogram-desktop)
- [Issue Tracker](https://github.com/darklord-end/jellogram-desktop/issues)
- [Telegram Official Website][telegram]

## Third-party

* Qt 6 ([LGPL](http://doc.qt.io/qt-6/lgpl.html)) and Qt 5.15 ([LGPL](http://doc.qt.io/qt-5/lgpl.html)) slightly patched
* OpenSSL 3.2.1 ([Apache License 2.0](https://www.openssl.org/source/apache-license-2.0.txt))
* WebRTC ([New BSD License](https://github.com/desktop-app/tg_owt/blob/master/LICENSE))
* zlib ([zlib License](http://www.zlib.net/zlib_license.html))
* LZMA SDK 9.20 ([public domain](http://www.7-zip.org/sdk.html))
* liblzma ([public domain](http://tukaani.org/xz/))
* Google Breakpad ([License](https://chromium.googlesource.com/breakpad/breakpad/+/master/LICENSE))
* Google Crashpad ([Apache License 2.0](https://chromium.googlesource.com/crashpad/crashpad/+/master/LICENSE))
* GYP ([BSD License](https://github.com/bnoordhuis/gyp/blob/master/LICENSE))
* Ninja ([Apache License 2.0](https://github.com/ninja-build/ninja/blob/master/COPYING))
* OpenAL Soft ([LGPL](https://github.com/kcat/openal-soft/blob/master/COPYING))
* Opus codec ([BSD License](http://www.opus-codec.org/license/))
* FFmpeg ([LGPL](https://www.ffmpeg.org/legal.html))
* Guideline Support Library ([MIT License](https://github.com/Microsoft/GSL/blob/master/LICENSE))
* Range-v3 ([Boost License](https://github.com/ericniebler/range-v3/blob/master/LICENSE.txt))
* Open Sans font ([Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0.html))
* Vazirmatn font ([SIL Open Font License 1.1](https://github.com/rastikerdar/vazirmatn/blob/master/OFL.txt))
* Emoji alpha codes ([MIT License](https://github.com/emojione/emojione/blob/master/extras/alpha-codes/LICENSE.md))
* xxHash ([BSD License](https://github.com/Cyan4973/xxHash/blob/dev/LICENSE))
* QR Code generator ([MIT License](https://github.com/nayuki/QR-Code-generator#license))
* CMake ([New BSD License](https://github.com/Kitware/CMake/blob/master/Copyright.txt))
* Hunspell ([LGPL](https://github.com/hunspell/hunspell/blob/master/COPYING.LESSER))
* Ada ([Apache License 2.0](https://github.com/ada-url/ada/blob/main/LICENSE-APACHE))

## Build instructions

* [Windows (32-bit and 64-bit)](https://github.com/darklord-end/jellogram-desktop/blob/dev/docs/building-win.md)
* [macOS](https://github.com/darklord-end/jellogram-desktop/blob/dev/docs/building-mac.md)
* [GNU/Linux using Docker](https://github.com/darklord-end/jellogram-desktop/blob/dev/docs/building-linux.md)

## License

This project is licensed under the GPLv3 with OpenSSL exception – see the [LICENSE](https://github.com/darklord-end/jellogram-desktop/blob/dev/LICENSE) file for details.

[telegram]: https://telegram.org
[telegram_api]: https://core.telegram.org
[telegram_proto]: https://core.telegram.org/mtproto
[license]: https://github.com/darklord-end/jellogram-desktop/blob/dev/LICENSE
