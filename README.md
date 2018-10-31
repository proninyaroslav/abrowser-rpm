RPM package of Abrowser
=====================

RPM packages of Abrowser - GNU Trisquel's version of Firefox [https://trisquel.info/en/wiki/abrowser-help](https://trisquel.info/en/wiki/abrowser-help).

You can download prebuilt RPM's from [Release](https://github.com/proninyaroslav/abrowser-rpm/releases) section or from [mirror](https://proninyaroslav.ru/ftp/abrowser_rpm/).

## Dependencies

 - `alien`
 - `rpmrebuild`

## Building

Build script is a converter of the original DEB package to RPM using `alien` and `rmprebuild`. This dependencies must be manually installed.

Usage: `abrowser_deb2rpm [DEB_FILE_PATH]`
