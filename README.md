# Variable Font Slant Test for Web Browsers

Browser support for the *Slant* axis in web browsers is uncertain. This project is meant to be a simple test of how well this is working.

https://arrowtype.github.io/vf-slnt-test/

<h2>Results as of Jan 27, 2020</h2>

All tested browsers support <code>font-variation-settings: 'slnt' -10</code>, but support for <code>font-style: oblique XXdeg</code> is much worse. As tested on macOS, Windows, iOS, and Android:

<ul>
<li><b>Chrome (81.0.4040.0):</b> No support.</li>
<li><b>Android 9.0 Chrome</b>No support.</li>
<li><b>Safari (13.2, WebKit 15610.1.1):</b> No support.</li>
<li><b>Safari iOS 13:</b> No support.</li>
<li><b>Edge (79 Beta):</b>No support.</li>
<li><b>Opera (67):</b>No support.</li>
<li><b>Firefox (72.0a1, 72.0.2):</b> Closest to support, but only shows clockwise slant for a *negative* oblique value (opposite of what should happen, per CSS spec).</li>
</ul>