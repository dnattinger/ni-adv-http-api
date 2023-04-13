# ni-adv-http-api

[![LabVIEW](https://img.shields.io/badge/LabVIEW-2019-%23E37725.svg?)](https://www.ni.com/en-us/shop/labview/select-edition/labview-community-edition.html)
[![Image](https://www.vipm.io/package/ni_lib_advanced_http_client_api/badge.svg?metric=installs)](https://www.vipm.io/package/ni_lib_advanced_http_client_api/)
[![Image](https://www.vipm.io/package/ni_lib_advanced_http_client_api/badge.svg?metric=stars)](https://www.vipm.io/package/ni_lib_advanced_http_client_api/)

The NI Advanced HTTP Client API is intended to be a replacement for the HTTP Client API (Data Communication > Protocols > HTTP Client) that ships with LabVIEW. This new API includes multiple benefits over the existing LabVIEW API including:

1. Support for the PATCH verb.
2. Support for any arbitrary HTTP verb via a 'Generic Request' VI.
3. Better compatibility with newer HTTP versions.
4. Multithreading safe operations.

The new VIs are available in the Addons subpalette when the package is installed. The source code in this repo is saved in LabVIEW 2019 and the VIPM .vipb file was created with VIPM 2019. This API is intended to support LabVIEW 2019 and later, 32-bit and 64-bit, Windows only.
