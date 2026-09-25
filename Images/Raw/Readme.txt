________________________________________________________________________________
Naming Convention

Raw pixel data file names follow the convention:
PixelFormat_WidthxHeight_ColourSpace_Offset_RowOrder_SurfOrMipCount_Source.raw

ColourSpace:
  sRGB or lRGB.

Offset:
  A 3-digit number with leading zeroes that is the offset count in bytes to the
  actual pixel data in the file.

RowOrder:
  NR for no row-reversal.
  RR for row reversal.

SurfOfMipCount:
  SNN for surfaces. NN is the count with possibly a leading zero.
  MNN for mipmaps.  NN is the count with possibly a leading zero.

Source:
  The image the raw data is based on.
  DSK if it is the Desk.exr image,
  TTP if it is the TacentTestPattern.
  DOK if it is the Dock photo.
  CUB if it is a Tacent cubemap side image.

________________________________________________________________________________
