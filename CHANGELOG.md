# Change Log

# 1.15.0
* Additionally export history as CSV file
* Color tool and system bars when a view is scrolled
* Add an intent filter for opening images
* Add Russian translation

# 1.14.0
* Add OTP support
* Update Indonesian translation

# 1.13.1
* Fix crash caused by missing support for Regex on Android < 6

# 1.13.0
* Add missing extras for ZXing result intents

# 1.12.0
* Add preferences dialog and the option to use a custom URL with read contents
* Add Brazilian Portuguese translation
* Add Chinese translation
* Encode text using UTF-8 encoding when creating a barcode

# 1.11.2
* Downgrade ZXing version
* Improve getting system UI metrics

# 1.11.1
* Fix tap to focus on some devices

# 1.11.0
* Add support for VCard and VEvent barcodes contents
* Generated barcodes are now zoomable
* Fix creating PDF417 barcodes

## 1.10.0
* Add support for special barcode contents (WiFi, SMS, phone, E-mail)
* Add Indonesian translation
* Update Hungarian translation
* Make system bars completely transparent

## 1.9.1
* Pick search engine for content that is not an URL

## 1.9.0
* Try Google when opening content as URL fails
* Show generic error message if barcode generation fails

## 1.8.1
* Distribute APK instead of App Bundle

## 1.8.0
* Save binary data into external file
* Fix storage of binary data
* Remove horizontal orientation line from scanner

## 1.7.3
* Fix crashes on Lineage and remove RenderScript fallback
* Improve handling of binary data

## 1.7.2
* Add a fallback for RenderScript
* Add italian translation

## 1.7.1
* Fix support for 64 bit architectures

## 1.7.0
* Pick list separator on sharing history listing
* Update Hungarian translation

## 1.6.0
* Share history listing as plain text
* Add separator line between history items
* Add content description for floating action buttons

## 1.5.1
* Fix generating hex dump

## 1.5.0
* Show a hex dump of decoded contents
* Fix processing text from share menu
* Add French translation

## 1.4.3
* Fix broken history listing

## 1.4.2
* Show barcode type and content length after decoding

## 1.4.1
* Toggle availability of torch mode button according to camera features

## 1.4.0
* Save scanned codes and show a history listing
* Share generated barcodes
* Add scanning from a shared image
* Add menu item to switch between camera front/back camera
* Add dutch and hungarian translation

## 1.3.8
* Qualify for F-Droid

## 1.3.7
* Normalize URL schemes

## 1.3.6
* Fix handling of camera scene modes

## 1.3.5
* Add german translation
* Fix handling of data intents
* Respond to ZXing' SCAN intents

## 1.3.4
* Fix pre-processing for Android 7+
* Fix adaptive icons for Android 8+

## 1.3.3
* Improved pre-processing
* Added adaptive icon for Android 8+
* Decrease default magnification to 10%

## 1.3.2
* Fixed crash when going back very fast

## 1.3.1
* Changed primary color

## 1.3.0
* Support tap to focus
* Save chose zoom level permanently
* Update ZXing to latest version (3.3.2)

## 1.2.0
* Added a camera zoom slider
* Added an unobtrusive wallpaper background
* Replaced lock marks with just a horizontal line
* Put toggling torch mode into Floating Action Button

## 1.1.1
* Brought back inverting every second frame

## 1.1.0
* Create barcodes
* Streamlined video pre-processing
* Decoded content is editable now
* Fixed position of lock marks on tablets
* Open README from menu

## 1.0.1
* Keep proguard from messing with renderscript
