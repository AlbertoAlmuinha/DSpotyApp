
# DSpoty App Tutorial

[![Lifecycle:
maturing](https://img.shields.io/badge/lifecycle-maturing-blue.svg)](https://www.tidyverse.org/lifecycle/#maturing)

R Shiny Dashboard that shows multiple information based on DSpoty R
package.

## Opening App

You can open the app in this URL:
[DSpotyApp](https://albertoalmuinha.shinyapps.io/DSpotyApp/)

## Panels

DSpoty App has 3 main panels:

  - Artist
  - Albums
  - Tracks

![](https://github.com/AlbertoAlmuinha/DSpotyApp/blob/master/Images/app_panels.JPG)<!-- -->

## Messages and Notifications

You can see two symbols in the app header, messages and notifications.
Here you can get different links: to this App Tutorial, Author Github,
Author LinkdIn..

![](https://github.com/AlbertoAlmuinha/DSpotyApp/blob/master/Images/symbols.JPG)<!-- -->

## Panel 1: Artist Information

When you open the app, a default artist information will be loaded
(Arctic Monkeys). Probably, this information will last about 30-40
seconds to be shown. This is because we are getting back all the Spotify
artist associated information (albums, tracks, related artist…). For
this reason, the workflow app should always be:

1.  Pick an artist in the ‘Artist’ panel.
2.  Go to ‘Albums’ panel or ‘Tracks’ panel.

Both album panel and tracks panel are based on the information returned
in the first panel (artist).

If you want to pick an artist:

1.  Type the artist name in the box and click the ‘Update’ button.

![](https://github.com/AlbertoAlmuinha/DSpotyApp/blob/master/Images/artist_box.JPG)<!-- -->

2.  Wait until all the panel is displayed. This step is the most
    computational expensive and can take about one minute. The loaded
    panel should looks like this:

![](https://github.com/AlbertoAlmuinha/DSpotyApp/blob/master/Images/artist_panel.JPG)<!-- -->

In this panel you can see six valueBox with some artist information, a
gif with the top 20 related artist and an **artist image linked to the
Spotify page** of the selected artist. This means if you click the
image, you will be redirected to Spotify artist web.

## Panel 2: Albums Information

Once you have loaded the artist information, in the albums panel, all
the artist albums will be shown in the box:

![](https://github.com/AlbertoAlmuinha/DSpotyApp/blob/master/Images/album_box.JPG)<!-- -->

You can pick one of them and then click the ‘Update’ botton. The result
panel must be something similar:

![](https://github.com/AlbertoAlmuinha/DSpotyApp/blob/master/Images/album_panel.JPG)<!-- -->

**You can click the album image to be redirected to the album Spotify
web.**

## Panel 3: Tracks Information

Once you have loaded the artist information, in the tracks panel, all
the artist tracks will be shown in the box:

![](https://github.com/AlbertoAlmuinha/DSpotyApp/blob/master/Images/track_box.JPG)<!-- -->

The next steps are the following:

  - Pick one of the artist tracks in the box and click the ‘Pick a Song’
    botton. The result panel should be like this:

![](https://github.com/AlbertoAlmuinha/DSpotyApp/blob/master/Images/track_1.JPG)<!-- -->

You can see an audio gadget to listen the song and 3 value boxs (the
last one redirects you to the song Spotify web).

  - Click the ‘Search Similar Songs’ button. The result panel should be
    like this:

![](https://github.com/AlbertoAlmuinha/DSpotyApp/blob/master/Images/track_2.JPG)<!-- -->

You can see a table with the information of the similar songs and also
the ‘similar songs box’ will have choices to pick.

  - Finally, you can pick a similar song in the box and click the ‘Pick
    a song’ button under the box.

![](https://github.com/AlbertoAlmuinha/DSpotyApp/blob/master/Images/track_3.JPG)<!-- -->

You can see an image that redirects you to spotify song web and an audio
gadget. If you want to pick anoter artist information, return to
‘Artist’ panel and ‘Panel 1: Artist Information’ section.

## Issues

This shiny app is not finished and can suffer some changes. If you see
some errors, please, tell me here:
<https://github.com/AlbertoAlmuinha/DSpotyApp/issues>
