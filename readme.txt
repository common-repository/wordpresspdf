=== WordpressPDF ===
Contributors: Strangeqargo, Cristian Rusu, HanaDaddy
Donate link: http://rusterra.com/
Tags: pdf, embed, flash
Requires at least: 2.0
Tested up to: 2.8.5
Stable tag: 0.6.3
WordpressPDF uses zviewer to embed PDFs converted to swfs.

== Description ==
WordpressPDF uses zviewer to embed PDF files converted to swfs.
An easy iPaper-like interface for PDF documents, books, magazines.
View live demo on plugin's homepage.




== Installation ==

1. Upload the WordpressPDF plugin to your wordpress blog, Activate it.
2. Download swftools from http://www.swftools.org
3. Use pdf2swf on your pdf-file. Just throw your pdf on pdf2swf.
4. Upload swf to your site
5. embed swf with wp-pdf-view tag
	i.e. [wp-pdf-view  swf="/path/to/filename.swf" width="500" height="400" /]

== Frequently Asked Questions ==

= Double interface problem =

WordpressPDF currently doesn't support SWFs created with "embed player" feature of swftools, use 'raw' mode instead

= Slow response =

1. Use image compression when saving PDF (JPEG for images etc.),
2. Downsample images when saving PDF.

== Changelog ==
= 0.6.3 =
* feel free to test if this update fixes the_excerpt() problem (often found in categories/archives)

= 0.6.2 =
* some js-related bugs fixed, IE6+ should work ok now. Thanks to Cubus - http://www.cubus.be/

= 0.6.1 =
* search button fix

= 0.6 =
* 0.5 update had a pretty nasty bug: zviewer.swf was updated only in source folder, so you could not see any fixes, if you did not copy zviewer from source folde. my bad, i'm sorry
* so, 0.6 brings all the promised features of 0.5 plus extra:
* fixed annoying bug with loading big swf's (plays all the frames rapidly after loading)

= 0.5 =
* default best-fit zoom mode.
* default go to top of page on flipping.
* better textbox border-color.

= 0.4 =
* plugin output (javascript etc.) no longer goes into wordpress feeds.

= 0.3 =
* media upload fixed, thanks to Kev from www.kjktech.com
* p.s. you may need to restart your browser or hit ctrl+f5 to reload scripts

= 0.2 =
* page numbers display fixed
* post editor buttons fixed

= 0.1 =
* first version, testing