# Swftools
This is a customo version of Swftools 0.9.2 for Mac OS compilation

## Installation

1. Clone this repository in any directory
2. Inside the folder of this project execute `./configure` to configure with your system
3. Ones the project configured, type and run `make`
4. Finaly type and run `make install`

Ones the installation is comolete you should see the help options of the command when you execute one of the tools like this:

```
~/Desktop/swftools » pdf2swf                                                                                                                                          eaguilar@Eduardos-MacBook-Pro

Usage: pdf2swf [-options] file.pdf -o file.swf

-h , --help                    Print short help message and exit
-V , --version                 Print version info and exit
-o , --output file.swf         Direct output to file.swf. If file.swf contains '%' (file%.swf), then each page goes to a separate file.
-p , --pages range             Convert only pages in range with range e.g. 1-20 or 1,4,6,9-11 or
-P , --password password       Use password for deciphering the pdf.
-v , --verbose                 Be verbose. Use more than one -v for greater effect.
-z , --zlib                    Use Flash 6 (MX) zlib compression.
-i , --ignore                  Allows pdf2swf to change the draw order of the pdf. This may make the generated
-j , --jpegquality quality     Set quality of embedded jpeg pictures to quality. 0 is worst (small), 100 is best (big). (default:85)
-s , --set param=value         Set a SWF encoder specific parameter.  See pdf2swf -s help for more information.
-w , --samewindow              When converting pdf hyperlinks, don't make the links open a new window.
-t , --stop                    Insert a stop() command in each page.
-T , --flashversion num        Set Flash Version in the SWF header to num.
-F , --fontdir directory       Add directory to the font search path.
-b , --defaultviewer           Link a standard viewer to the swf file.
-l , --defaultloader           Link a standard preloader to the swf file which will be displayed while the main swf is loading.
-B , --viewer filename         Link viewer filename to the swf file.
-L , --preloader filename      Link preloader filename to the swf file.
-q , --quiet                   Suppress normal messages.  Use -qq to suppress warnings, also.
-S , --shapes                  Don't use SWF Fonts, but store everything as shape.
-f , --fonts                   Store full fonts in SWF. (Don't reduce to used characters).
-G , --flatten                 Remove as many clip layers from file as possible.
-I , --info                    Don't do actual conversion, just display a list of all pages in the PDF.
-Q , --maxtime n               Abort conversion after n seconds. Only available on Unix.
```
