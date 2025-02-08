![20250208 Tengwar Ariador Regular](https://github.com/user-attachments/assets/fa48620f-8e2e-48d3-825e-80c55b80bcb4)


# Tengwar Ariador
Tenwar Ariador Regular Open Type Font, v.1.21

© January 31 2025 by Igor Voloshin (Ariador)

Foundry: FontForge

License: SIL Open Font License v.1.1

Another font for the fictional Tengwar script developed by the great J.R.R.Tolkien for his immense Arda Universe. The font is free and open source (the FontForge SFD file is included). All the rights to the word "Tengwar" and the script itself belong to their respectful owners - the Tolkien Estate.

The goal of making another one Tengwar font is to achieve convenience of using the font with generic US English keyboard layout. The image of the glyphs layout '20250131 Tengwar Ariador US Layout.png' is enclosed. All the glyphs not directly available for typing are listed in the enclosed file '20250131 Tengwar Ariador Glyphs with Quenya Names.pdf' and are available for typing using Compose key. The glyphs span is limited by the Basic Latin and Latin-1 ISO 8859-1 character set. And of course, a text sample is included, a first stance of the glorious 'Namárië', for your viewing pleasure.

Issues to solve are the following:
  1. There are 12 unused glyph positions left in Latin-1 set, which could be filled with some missed tengwar, a matter of further studies;
  2. Kerning is not set so far, not at all. Anyway, LibreOffice still struggles to handle fonts kerning through all those years of development.
     Any inline format change disrupts the kerning not saying that Calc does not recognise kerning at all for the text processing formulae. For this reason I've concentrated on the glyphs form to compose them smoothly where it's possible without using kernings. Perhaps one day I'll try to do some, mostly for those seven sarincë glyphs;
  4. The practice shows some tehtar are not placed conveniently for quick typing in Quenya. Should try to improve the layout a bit;
  5. Diphtongs and ligatures are subject for autoreplace processing, therefore could be replaced in the keyboard layout with one-letter glyphs to get the typing more handy;
  6. Tiny improvements in some glyphs outline are possible to get better aesthetics;
  7. Special custom keyboard layout for the font is under development, to be embedded in Ubuntu system as separate Input Source allowing for typing all the glyphs in (almost) one touch using RightAlt key.

Edit of February 1 2025: Build 1.21 - Exchanged places for two pairs of glyphs to assign upper and lower yanta tehtar more handy - to Q and W letters in the keyboard. Also made space width 20% narrower, looks a tiny bit better.

Edit of February 2 2025: Build 1.22 - Added the font version with Dan Smith's keyboard layout - de facto standard for tengwar fonts since 1998. Perfect for true fans of Quenya, unconvenient for those wanting just type English with tengwar. See it in the files 'TengwarAriadorDS.otf', 'TengwarAriadorDS.sfd', '20250202 Tengwar Ariador Dan Smith's Layout.png'. Actually my layout differs from the original Dan Smith's and for good reason - anchoring tehtar allowed to use just one key for each techta instead of four. So I filled the spared keys with more glyphs, trying to put them conveniently. Woulld be good to know from you dear readers if I managed to nail the task.

Edit of February 4 2025: Build 1.23 - Any formatting of the tebgwa (base character) or tehta (accent) disrupts their combining because of non-printable formatting symbols inserted between the base and accent. To allow for different format of these two, 4 invisible glyphs added to place between format and accent: ¢ - narrow base; £ - single width base; ¤ - double width base and ¥ - lambe width base. Note: type these invisible bases after tengwa, then type tehta and only then go back to tengwa and format it. Now you can make tengwa and tehta different in color or even type tehtar over Latin letters. All four invisible glyphs are available with compose key: Compose + | + c = ¢; Compose + - + L = £; Compose + o + x = ¤; Compose + = + Y = ¥.

Edit of February 5 2025: Added same invisible glyphs to Dan Smith's layout, too - replaced 'TengwarAriadorDS.otf' and 'TengwarAriadorDS.sfd'. Also replaced Namárië with full text.
