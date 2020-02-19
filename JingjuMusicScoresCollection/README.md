# Jingju Music Scores Collection
The **Jingju Music Scores Collection** (**JMSC**) is part of the [**Jingju Music Corpus**](http://compmusic.upf.edu/corpora) created in the [**CompMusic** project](http://compmusic.upf.edu/). Created with the purpose of the melodic research of jingju singing lines, it contains 92 MusicXML scores, covering 899 melodic lines. In terms of the jingju musical system, it covers the following elements:
- **role type**: *laosheng*, *dan*
- **_shengqiang_**: *erhuang*, *xipi*
- **_banshi_**: *manban*, *sanyan*, *zhongsanyan*, *kuaisanyan*, *yuanban*, *erliu*, *liushui*, *kuaiban*

The scores are sourced from printed editions and created with [MuseScore 2.1.0](https://musescore.org/), including the lyrics. The original [*jianpu* notation](https://en.wikipedia.org/wiki/Numbered_musical_notation) is transnotated into staff notation. All the scores contain a separated staff for the accompaniment (jinghu) line.

## Content of the **JMSC**
The **JMSC** contains the following three folders:
- The `MusicXML` folder contains the MusicXML scores and the `scores_data.csv` and `lines_data.csv` files containing metadata and annotations.
- The `MuseScore` folder contains the scores created with MusicScore in its original format, from which the MusicXML scores were exported.
- The `AlignedScores` folder contain PDF files with all the melodic lines belonging to the same combination of role type, *shengqiang*, *banshi* and line type aligned in terms of line section. These files were used for the comparative analysis whose results are presented and discussed in Caro (2018).

## Annotations and metadata
The `MusicXML` folder of the **JMSC** contains the following two files with annotations and metadata.
- The `scores_data.csv` file contains metadata and annotations for each score. The included information consists of the following data: title of the aria (in Chinese), role type, *shengqiang*, *banshi*, 'yes' or 'no' the original score contained a separated line for the accompaniment, the reference to the printed source, and the MusicBrainz ID of related recordings.
- The `lines_data.csv` file contains annotations for each line in the **JMSC**. The included information consists of the following data: role type, *shengqiang*, *banshi*, line type, lyrics of the line, starting offset of the line, ending offset of the line, linguistic tones, lyrics of the first line section, starting offset of the first line section, ending offset of the first line section, lyrics of the second line section, starting offset of the second line section, ending offset of the second line section, lyrics of the third line section, starting offset of the third line section, and ending offset of the third line section. Regarding line types, 's' stands for opening line in *xipi*, 's1' for the long opening line type, and 's2' for the short opening line type in *erhuang*, and 'x' for closing line.

## Using the **JMSC**
Since the scores are sourced from copyrighted printed editions, they can be only shared for non commercial research purposes (see below). The metadata and annotations files are released under a [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0)](https://creativecommons.org/licenses/by-nc-nd/4.0/) license.

For referencing the **JMSC**, and obtaining a more detailed description of it, please refer to

Caro Repetto, Rafael (2018) *The musical dimension of
Chinese traditional theatre: An analysis from computer aided musicology*. PhD thesis, Universitat Pompeu Fabra, Barcelona, Spain.

## Contact
For any questions or comments about the **JMSC**, please contact  
  Rafael Caro Repetto  
  (rafael.caro@upf.edu)

## Acknowledgements
The creation of the **JMSC** is funded by the European Research Council under the European Union’s Seventh Framework Program (FP7/2007-2013), as part of the CompMusic project (ERC grant agreement 267583).
