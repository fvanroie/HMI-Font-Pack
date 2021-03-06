HMI Font Pack
=============

![Font Preview](https://github.com/fvanroie/HMI-Font-Pack/blob/v0.0.2/HMI%20KoHo-Regular%2028%20(WINDOWS_874).png)

About
-----

This HMI Font Pack contains a large selection of open-source fonts that can be used in Nextion / TJC HMI projects.
The Nextion Editor and TJC USART Editor use a propriatary .zi font format.
Now you can add a wide selection of quality fonts to your project in seconds.

In the font pack there are dozens of fonts for each supported language (codepage) in different fontsizes.
Only Regular styles are included in the current release.

The .zi files are version 5 and support anti-aliasing and variable width fonts. Version 0.55 or higher of the Nextion / USART HMI Editor is needed to use these font files.


Open Source Fonts
-----------------

The Open Source fonts used to create the HMI Font Pack include:

- Most of the fonts are from the general Google Fonts project: https://github.com/google/fonts
- Chinese, Japanese and Korean Noto fonts are from: https://github.com/googlefonts/noto-cjk
- Unicode Noto fonts are created using individual fonts from: https://github.com/googlefonts/noto-fonts

More OFL fonts can be included upon request.


Version History
---------------

| Date       | Version | Description
|:----------:|:-------:|----------------
| 2019-09-05 |  [0.0.2][2]  | - Fixed bug that could crash the Editor when the HMI layout is rotated 90°, 180° or 270°.<br>- Added two Unicode UTF-8 fonts.<br>- Each .zi file now also has an accompanying .png preview image.
| 2019-08-19 |  [0.0.1][1]  | Initial Release

Click the versionnumber to go to the Realease download page.

[1]: https://github.com/fvanroie/HMI-Font-Pack/releases/tag/v0.0.1-alpha
[2]: https://github.com/fvanroie/HMI-Font-Pack/releases/tag/v0.0.2-alpha

License
-------

Most of the fonts in the HMI Font Pack are distributed under the SIL Open Font License, v1.1.
Some fonts use the Apache 2 license. The Ubuntu fonts are released under the Ubuntu Font License v1.0.
The HMI Font Pack files are licensed under the same open license as the source fonts.

The Reserved Font Names are copyrighted by their respective owners.
Each HMI font is prepended with the text "HMI" to indicate a derived work and it has the .zi file extension.
No changes were made to the original .ttf or .otf files. Each .zi file basically contains a bitmap render of the original characters.

The zip archive contains subfolders per license type:
- OFL : SIL Open Font License, Version 1.1
- UFL : Ubuntu Font License, Version 1.0
- Apache2 : Apache License, Version 2.0

The original license files for each Open Source font are retained in each font directory.
Carefully read the license file before including the HMI font files into your HMI projects.


Disclaimer
----------

The HMI font files are automatically generated by an early release version of [ZiLib](https://github.com/hagronnestad/nextion-font-editor/tree/master/NextionFontEditor/ZiLib). No guarantees are made towards the usability or suitablilty of these font files in your HMI projects.

Please open an [issue](https://github.com/fvanroie/HMI-Font-Pack/issues) if you find an error, bug or mistake.
