Here we provide a number of tutorials, presented in increasing complexity, designed to walk through the use of Autocnet.
Some of the data is stored remotely (due to the size).  In these cases the tutorial provides links to download the data.
All tutorials are rendered in plain text in the documentation, but are available for interactive use by cloning our github
repository at <https://github.com/USGS-Astrogeology/autocnet>_.

Working With ISIS Control Networks
-------------------------------
.. toctree::
   :maxdepth: 1

    Ingesting from ISIS control network<isis_ingestion/from_cnet.ipynb>
    Check for empty overlaps and overlap connectivity<isis_ingestion/overlap_check.ipynb>
    Using outlier detection to check for bad measures<outlier_detection/outlier_detection.ipynb>


Working With Apollo Pan
-----------------------
.. toctree::
   :maxdepth: 1

    Creating the CandidateGraph Object<apollopan/1. Creating the CandidateGraph Object.ipynb>
    Extracting Keypoints (Interest Points) <apollopan/2. Extracting Keypoints (Interest Points).ipynb>
    Matching <apollopan/3. Matching.ipynb>
    Fundamental Matrix <apollopan/4. Fundamental Matrix.ipynb>
    Coupled Decomposition - Part I <apollopan/5a. Coupled Decomposition - Part I.ipynb>
    Coupled Decomposition - Part II <apollopan/5b. Coupled Decomposition - Part II.ipynb>
    Coupled Decomposition - Part III <apollopan/5c. Coupled Decomposition - Part III.ipynb>
    Subpixel Matching - Part I <apollopan/6a. Subpixel Matching - Part I.ipynb>
    Subpixel Matching - Part II <apollopan/6b. Subpixel Matching - Part II.ipynb>
    Saving and Loadin <apollopan/7. Saving and Loading.ipynb>
    Adding Correspondences Using Constraints <apollopan/8. Adding Correspondences Using Constraints.ipynb>
    Creating a Control Network <apollopan/9. Creating a Control Network.ipynb>
    Advanced: Extending the CandidateGraph<apollopan/Advanced 1. Extending the CandidateGraph.ipynb>

Change Detection
----------------
.. toctree::
   :maxdepth: 1

   Change detection examples<change_detection/Change_Detection.ipynb>
