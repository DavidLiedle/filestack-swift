Change Log
==========

Version 1.2.7 *(2018-07-18)*
----------------------------

- Fix test target.

Version 1.2.6 *(2018-06-20)*
----------------------------

- Added new image content detection transforms.

Version 1.2.5 *(2018-06-18)*
----------------------------

- Added new Transforms.
- Moved some Transform related string to enums.


Version 1.2.4 *(2018-06-11)*
----------------------------

- Added `MultifileUpload` class.


Version 1.2.3 *(2018-06-01)*
----------------------------

- Updated CryptoSwift to version 0.10.0.

Version 1.2.2 *(2017-12-19)*
----------------------------

- Added @objc decorator to MultipartUpload's `cancel()` function.

Version 1.2.1 *(2017-12-19)*
----------------------------

- Updated CryptoSwift and Alamofire dependencies.
- Upgraded code to Swift 4.

Version 1.2 *(2017-11-20)*
----------------------------

- Migrated from Arcane to CryptoSwift.

Version 1.1 *(2017-11-03)*
----------------------------

- Added support for store options to uploads functionality.
- Improved upload error reporting.

Version 1.0.2 *(2017-11-01)*
----------------------------

- Disabled new Xcode build system to prevent issues with Carthage builds.
- Updated Arcane dependency to version 1.0.
- Updated Alamofire dependency to version 4.5.1.

Version 1.0.1 *(2017-10-31)*
----------------------------

- Added `startUploadImmediately` argument and turning `localURL` into an optional argument in `Client` `multipartUpload` function.
- Declared `MultipartUpload` `uploadFile()` function public.
- Added `StorageOptions` class.

Version 1.0 *(2017-08-23)*
----------------------------

Initial release.
