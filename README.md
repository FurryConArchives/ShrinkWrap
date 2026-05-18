# shrinkwrap

A lightweight C utility to downscale documents while preserving the legibility of embedded, rasterized text. 

Instead of uniform compression (which ruins text), `shrinkwrap` segments text regions, downscales the background layers independently, and re-composites the sharp text back on top.
