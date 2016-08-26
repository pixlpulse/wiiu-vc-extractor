# wiiu-vc-extractor
Extracts Wii U Virtual Console roms from dumps created via DDD

This currently only supports extracting NES and SNES roms. Note that most VC titles are not clean roms but have been modified from their original state.

## Basic Usage
`WiiuVcExtractor \<rpx_file\> \<target_file\>`

`WiiuVcExtractor WUP-FCSE.rpx "Mega Man 6.nes"`


## Credits
Decompression of rpx files is possible due to the following tool created by 0CBH0:
https://github.com/0CBH0/wiiurpxtool
