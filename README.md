# ni-adv-http-api

The NI Advanced HTTP Client API is intended to be a replacement for the HTTP Client API (Data Communication > Protocols > HTTP Client) that ships with LabVIEW. This new API includes multiple benefits over the existing LabVIEW API including:

1. Support for the PATCH verb.
2. Support for any arbitrary HTTP verb via a 'Generic Request' VI.
3. Better compatibility with newer HTTP versions.

The new VIs are available in the Addons subpalette when the package is installed. The source code in this repo is saved in LabVIEW 2019 and the VIPM .vipb file was created with VIPM 2019. This API is intended to support LabVIEW 2019 and later, 32-bit and 64-bit, Windows only
