# christmascarolforbinders
This is a XeLaTex rendering into PDF of the 1915 edition of Charles Dickens' _A Christmas Carol_, intended for use by DIY bookbinders. Project Gutenberg original is at https://www.gutenberg.org/cache/epub/24022/pg24022-images.html

If you are using US letter size paper:
* Download files
  * lettersignature0duplex.pdf
  * lettersignature1duplex.pdf
  * lettersignature2duplex.pdf
  * lettersignature3duplex.pdf
  * lettersignature4duplex.pdf
  * lettersignature5duplex.pdf
  * lettersignature6duplex.pdf
* Print out double-sided, flip on short side

If you are using A4 size paper:
* Download files
  * a4signature0duplex.pdf
  * a4signature1duplex.pdf
  * a4signature2duplex.pdf
  * a4signature3duplex.pdf
  * a4signature4duplex.pdf
  * a4signature5duplex.pdf
  * a4signature6duplex.pdf
* Print out double-sided, flip on short side


The TeX originals are included in the source directory as accletter.tex and acca4.tex. They expect to find their images in a subfolder called "images" (in the folder where you run TeX) and they use the following packages:
* graphicx
* xcolor
* fontspec
* fontenc
* makeidx
* lettrine
* scrlayer-scrpage
* pifont
* enumitem
* caption
* csquotes
* adjustbox
* babel
* ebgaramond

They expect the following fonts installed:
* Menuetto https://www.1001freefonts.com/menuetto.font
* Acorn Initials https://www.1001freefonts.com/acorn.font
