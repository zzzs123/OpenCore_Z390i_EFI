# OpenCore_Z390i_EFI
ASUS ROG Strix Z390 ITX
* agdpmod=pikera: Used for disabling boardID on Navi GPUs(RX 5000 series), without this you'll get a black screen. Don't use if you don't have Navi(ie. Polaris and Vega cards shouldn't use this)
* keepsyms=1: This is a companion setting to debug=0x100 that tells the OS to also print the symbols on a kernel panic. That can give some more helpful insight as to what's causing the panic itself.
