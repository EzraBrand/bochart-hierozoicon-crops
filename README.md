# bochart-hierozoicon-crops

Temporary image crops for [bochart-hierozoicon](https://github.com/EzraBrand/bochart-hierozoicon):
page halves and single printed lines of Bochart, *Hierozoicon*, ed. Rosenmüller (Leipzig 1793–96),
cut from the scans of the Bayerische Staatsbibliothek München (MDZ).

**Why this repository:** the OpenRouter Batch API (half price) takes images only as public URLs,
and the MDZ IIIF server is too slow for the batch providers to fetch crops in time. The pipeline
(`crophost.py`) writes the crops of one run here, pushes them, sends their raw URLs in the batch,
and clears the repository again with a force push when the run is done. The history is not kept.

**Rights:** the scans are by the Bayerische Staatsbibliothek München (MDZ), rights statement
[NoC-NC 1.0](https://rightsstatements.org/vocab/NoC-NC/1.0/) (no copyright, non-commercial use
only). Source: https://www.digitale-sammlungen.de/ (vol. 2 = bsb10353454). The text is in the
public domain.
