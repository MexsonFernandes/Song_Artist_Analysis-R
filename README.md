# `Songs Artist Analysis using geniusR`

R script to analyze two different music artist based on the words used in albums or songs. I have used geniusR library to gather the songs lyrics.

<a href='https://ko-fi.com/Y8Y31LBT4' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://cdn.ko-fi.com/cdn/kofi3.png?v=2' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>

# Requirements (R libraries):
  - geniusR (to mine song lyrics)
  - tidyverse (to manipulate data and for visualization)
  - tidytext (to tokenize dataset, remove stop words and count word frequency).
  
 
# Credits:
  - <a href="http://www.deeplytrivial.com/2018/05/statistics-sunday-taylor-swift-vs-lorde.html">Deeply Trivial - Statistics Sunday (May 13, 2018)</a>
  - <a href="https://github.com/JosiahParry/geniusR">GeniusR repo</a>
  
# Installation:
  - install.packages("devtools")
  - devtools::install_github("josiahparry/geniusR")
  - install.packages("tidyverse")
  - install.packages("tidytext")
  
# for album:
  Ed_Sheeran = genius_album(artist = "Ed Sheeran", album = "Divide")

# for singles:
  Shawn_Mendes_lyrics = genius_lyrics(artist = "Shawn Mendes", song = "In My Blood")
  
# Sample:
  <img src="sample.png" width="640px" height="480px">
