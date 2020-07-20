This figure shows the effect of changing the "near neighbors radius ratio" in the Hough circle transform plugin.  The left panel shows the input data with a single circle on top and a pair of overlapping circles below.  The next panel shows the resulting Hough circle transform (24 steps).  

The top right pair of panels show the effect of a clear ratio of 1.0, where when the first overlapping circle is found, the centroid of the neighboring circle is removed, resulting in only two high scoring circles being found. 

The bottom right pair of panels show the effect of a clear ratio of 0.2, where when the first overlapping circle is found, only its centroid is removed and the neighboring centroid is preserved for the neighboring circle to also be found, resulting in all three circles being found.

== Licensing ==
{{cc-by-sa-4.0}}