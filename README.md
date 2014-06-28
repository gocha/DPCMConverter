DPCMConverter
=============

**[Try DPCMConverter.swf Now!](http://gocha.s151.xrea.com/onlinetool/DPCMConverter.swf)**

Flash-based NES DPCM converter for [FlMML](http://flmml.codeplex.com/). Initial version is created by [arche](http://dic.nicovideo.jp/u/934152).

This version fixes several important bugs, and adds a little more conversion options.

- Fixed: Wrong delta conversion **(IMPORTANT BUGFIX!)**
- Fixed: Add padding bytes to respect NES DPCM size boundary (1+16n)
- Added: Conversion without sample rate conversion (good for oversampling for FlMML use)
- Added: Volume reduction option
