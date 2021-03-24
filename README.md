# irfont
This repository is made to access Persian fonts.
# Information about web fonts
Arrange fonts by Size and Name : <br>
100 - Thin<br>
200 - Ultra Light<br>
300 - Light<br>
400 - Regular OR Normal<br>
500 - Medium<br>
600 - Semi-bold OR Demi-Bold<br>
700 - Bold<br>
900 - Black<br>
## Support Browser
Font format<br>
TTF/OTF	✅   All Browser Supported<br>
WOFF    ✅	  All Browser Supported<br>
WOFF2   ✅	  All Browser Supported<br>
SVG     📲   Only iOS browsers are supported<br>
EOT     e    Only Edge browser supported<br>
# How To Use Github repository as cdn ?
The description of each font folder is given, but in general:<br>
What those two have in common is that by changing the hostname in a github link, for example:<br>
https://github.com/ProgYaghouti/irfont/Mikhak/Mikhak-Black.ttf<br>
to a hostname of the CDN service JSDelivr:<br>
https://cdn.jsdelivr.net/gh/progyaghouti/irfont/mikhak/Mikhak-Black.ttf<br>
...your files are available from the CDN just like so 😊.
## install Font with Css
@font-face {<br>
  font-family: Vazir;<br>
  src: url(https://cdn.jsdelivr.net/gh/progyaghouti/irfont/mikhak/Vazir-Thin.ttf);<br>
  font-weight: 100;<br>
}
## How To Use Font For TEXT class name
.TEXT {<br>
  font-family: Vazir;<br>
}<br>
