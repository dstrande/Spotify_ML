# 2026 note
I found that the high model accuracy was due to data leakage. 
Duplicates were being pulled during the randomized API process and not corrected for after. 
Further testing showed that the R² fell to 0.27.

# Spotify_ML
An attempt to use machine learning to fit Spotify audio features to Spotify "Popularity" index.
See the Spotify_ML.pdf for a brief overview and the code for more in depth information.

create_data.ipynb creates a csv of Spotify songs for late use (you need your own API key for this). <br>
data_fitting.ipynb is the analysis and machine learning notebook. <br>
XGB_fitting.ipynb is the XGB version of machine learning analysis. <br>

Note: these notebooks were created using the VSCode notebook extension.
There seems to be compatibility between Jupyter Lab and VSCode (relating to the EOL terminators used in both).
