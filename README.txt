A fresh new repo for small PDF utilities.

### rgb2cmyk.sh

    ./rgb2cmyk.sh input.pdf

This will convert a PDF to input-cmyk.pdf


### colorSeparation.sh

    ./colorSeparation.sh input-cmyk.pdf

This makes black and white images of each CMYK plates and makes a small
HTML page to preview the plates. It will output blank plates if your PDF is in
RGB.


Web interface for coloured preview of each plate:

![](http://osp.constantvzw.org/api/osp.tools.PDFutils/bf1d20aadcbc417dbcbf9b7d2ffbfb1f63aa4339/blob-data/all.png)
![](http://osp.constantvzw.org/api/osp.tools.PDFutils/bf1d20aadcbc417dbcbf9b7d2ffbfb1f63aa4339/blob-data/cyan.png)
![](http://osp.constantvzw.org/api/osp.tools.PDFutils/bf1d20aadcbc417dbcbf9b7d2ffbfb1f63aa4339/blob-data/magenta.png)
![](http://osp.constantvzw.org/api/osp.tools.PDFutils/bf1d20aadcbc417dbcbf9b7d2ffbfb1f63aa4339/blob-data/yellow.png)
![](http://osp.constantvzw.org/api/osp.tools.PDFutils/bf1d20aadcbc417dbcbf9b7d2ffbfb1f63aa4339/blob-data/black.png)

By zooming out, you can see several pages at the same time:
![](http://osp.constantvzw.org/api/osp.tools.PDFutils/bf1d20aadcbc417dbcbf9b7d2ffbfb1f63aa4339/blob-data/many-pages.png)
