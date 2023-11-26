# Vieo Generator for Jetsam Dreams

This repository contains IPython notebooks that were used to create video content for the album *Jetsam Dreams* by *Aerodactylus*. The resulting video can be viewed [here on YouTube](https://youtu.be/vkKwFKCnxnw). 

## Required Audio and Image Files

To generate the video files you will need the audio files for the Jetsam Dreams album and the cover art image. You can purchase these [here on BandCamp](https://aerodactylus.bandcamp.com/album/jetsam-dreams).

## Dependencies

This project is created using the tools of the `aeroaudioviz` package (https://github.com/Aerodactylus/AerAudioViz) and requires `jupyter`. Dependencies can be installed with `poetry` by running `poetry install`.

## Usage
Run the IPython Notebooks using `jupyter`, for example by running `poetry run jupyter lab` if you have installed dependencies using `poetry`.

Notebooks numbered 1 - 8 use the `aeraudioviz` package to create an mp4 video file for each of the tracks on *Jetsam Dreams*. After having run all 8 of these notebooks and successfully generated the video files, the final notebook, ("9. Generate Full Album Video.ipynb") can then be run to create the full album video (including transitions between tracks). 

Note that these are long-running and memory-intensive applications. 
