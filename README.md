# Anuran-Call-Classification
Identify the Genus of the anuran species from its call
This dataset is related to the challenge of anuran species recognition through their calls. The anurans are divided in families, genus and species.This dataset was created segmenting 60 audio records belonging to 8 genus. Each audio corresponds to one specimen (an individual frog).

 

After using the spectral entropy and a binary cluster method to detect audio frames belonging to each syllable a total of 5000 syllables were found.From each of them 22 Mel-frequency cepstral coefficients (MFCCs) were calculated. These coefficients were normalized between -1 and 1. MFCCs are coefficients that collectively make up a mel-frequency cepstrum (MFC).

 

The dataset comprises Cepstral features, which contain information about the rate changes in the different spectrum bands. The influence of the vocal cords and the vocal tract in a signal can be separated since the low-frequency excitation and the formant filtering of the vocal tract are located in different regions in the cepstral domain. The first-order coefficient represents the distribution spectral energy between low and high frequencies ( normally low frequency regions represent sonorant sound while high frequency regions represent fricative sound). The lower order coefficients contain most of the information about the overall spectral shape of the source-filter transfer function while higher order coefficients represent increasing levels of spectral details.

 

Your Task is to devise a Machine Learning Model that helps us to identify the Genus of the respective Anuraan species using only its call.
