# Thornton lab tool kit

A collection of useful scripts for doing some of the more annoying tasks involved in writing a paper

## compress_images.sh

* Requires: [ImageMagick](http://www.imagemagick.org/)
* Input: 600dpi tif, which will be massive.
* Output: A compressed tif that passes PLoS QC filters, and a high-quality PDF generated from that compressed tif usable
in a LaTeX situation.
* Recommendation: Workflows in R, Python should output 600dpi tif instead of pdf, and then apply this script.
Credit: Jaleal Sanjak
