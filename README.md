# Spotify Analysis
WIP: Analysis of Billboard Hot 100 tracks in conjunction with Spotify's Echo Nest API

# Datasets
### billboard-hot-100-tracks.csv
> Contains every Hot 100 chart up until the week of 11/6/2021

Burati, D. (2021). *Billboard Hot 100 - Full History* (Version 3) [Data set]. https://www.kaggle.com/datasets/dylanburati/billboard-hot-100-full-history?resource=download

### full_dataset.csv
> Contains the data from *billboard-hot-100-tracks.csv* combined with data for those associated songs from Spotify's Web API

### weekly_avgs.csv
> Averages (or counts occurances of, in the case of explicit music, major keys, and common time) all the available song data (*full_dataset.csv*) for each metric every week to get a broader picture of the week as a whole. A simple arithmetic mean is used. All tracks for a given week have the same weight in the calculation.

<hr>
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>
