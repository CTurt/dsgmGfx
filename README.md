dsgmGfx
=======
Customised version of PAGfx for DS Game Maker.

PAlib references are mostly removed.

16cFonts do not share tiles, so can be used with libnds console (and subsequently as a DS Game Maker Custom Font).

## Usage
Create a new file called `PAGfx.ini` in the same directory as `dsgmGfx` based on the following template. Run `dsgmGfx`, and the converted graphics will appear in a new directory called `bin`.

    #TranspColor Magenta
    #Textures :
    archvile.png 16bit
    
    #Backgrounds : 
    marioMap.png EasyBG
    ComicSans.png 16cFont
    
    #Sprites : 
    player.png 256Colors DSGMPal0