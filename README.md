# Meta-analysis with some robustness to publication bias
A version of meta.py script used by Neurosynth that will additionally determine the amount of contra-evidence required to overturn a significant effect within a voxel (i.e., association betweeen text-mined data about neuroiamging publications and activity).

You can replace Neurosynth's meta.py with this version--if contra-evidence is not requested, it will act in the same way as meta.py. Otherwise, you will see additional file outputs corresponding to "bias-corrected" forward/reverse inference maps.
