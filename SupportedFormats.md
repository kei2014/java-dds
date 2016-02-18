# Supported #

## Uncompressed ##
  * 1-8bit per color in RBG, Luminance, Alpha
  * A2RBG10 and A2GBR10

## Compressed ##
  * DXT1 / BC1
  * DXT2 / BC2
  * DXT5 / BC3 + yCoCg, yCoCg scaled, Alpha Exponent (Convert to RBG with the DDSUtil class)
  * ATI1 / BC4
  * ATI2 / BC5
  * DX10 in the above formats
<br>
<h1>NOT Supported</h1></li></ul>

<h2>Uncompressed ##

  * 16bit/32bit per color
  * Color formats VU, CxVU, QWVU, Palette

## Compressed ##
  * DXT3
  * DXT4

## Not included in 1.0.0 ##
Added in [r33](https://code.google.com/p/java-dds/source/detail?r=33):
  * YUV for uncompressed formats _(untested)_
  * RGBG, GRGB, UYVY, YUY2 compressed formats
  * DXT5nm