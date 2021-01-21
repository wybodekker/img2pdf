# img2pdf
|     key | description
|     ---:|:---
|  script | img2pdf - convert one or more image files into a multipage pdf
|    type | bash
|  author | Wybo Dekker
|   email | wybo@dekkerdocumenten.nl
| version | 0.00
| license | GNU General Public License

img2pdf creates a pdf file from one or more image files (any image format
understood by ImageMagick.) The pdf is written on standard output, unless the
--output option is used. However, img2pdf refuses to write its pdf output to
the terminal; you must redirect it to a file or a pipe.
