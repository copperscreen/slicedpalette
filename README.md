This is a retro-computing project. Beware!
It's a <a href="https://en.wikipedia.org/wiki/Hold-And-Modify#Sliced_HAM_mode_(SHAM)">sliced palette</a> image quantizer. 
Sliced palette means palette reloaded every line. Quantisation is performed by median cut & modified k-means
(if the number of clusters is too low the outliers are used as the new cluster seeds).
Resulting palette is displayed on the right. R/G/B input fields are used to limit color bandwidth (bits per channel).</span>

To run it just open the index.html in your browser.
