# CGA2Svideo
Circuits for converting digital RGBI (CGA) to S-video and other formats

This repo contains a collection of video conversion circuits intended
to convert old-fashioned digital RGBI monitor output as used by the
IBM PC Color Graphics Adapter (CGA) and several other 80's vintage small
computers to more modern and/or more available monitors. (RGBI is a thoroughly obsolete format; there have been very few monitors built since the early 1990's that are able to natively accept it.)

The titular circuit for this repository is a converter that uses an [Analog Devices AD724JR](https://www.analog.com/media/en/technical-documentation/data-sheets/AD724.pdf) NTSC/PAL encoder along with a GAL16v8 to turn RGBI video into both composite and separated Luma/Chroma (Svideo) output that can be fed into television sets and monitors that have the appropriate input jacks. The Luma/Chroma conversion specifically may be of interest to owners of monitors like the very common Commodore 1701/1702, which were designed to accept this type of input from Commodore 64 computers.

SVideo has lower color resolution than RGB, so the output from this circuit will be inferior to that of a true RGB monitor. But it still provides much clearer output, expecially at 80 columns, than the native composite video jack built into older PC compatible computers. This circuit might particularly be appealing to users of the Tandy 1000 series of computers, as the output is set up to better match the colors you get on an RGBI monitor (verses the odd palette that's normal for CGA composite) and the clarity is more than adequate for 320x200x16 color games.

