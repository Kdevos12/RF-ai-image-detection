# RF-ai-image-detection
Detection of AI generated image using random forest on various indicators obtained from images.  

The indicators used in this project include the mean and standard deviation of pixel values, skewness and kurtosis, the mean and maximum magnitudes from Fourier analysis, GLCM correlation (texture coherence), gray-level non-uniformity (GLNU), texture entropy, fractal dimension, Short Run Emphasis (GLRLM), spatial variance, edge density and distribution, as well as sharpness. These features capture statistical, textural, and structural aspects of the images for classification purposes.

Managed to obtain a 0.81 F1-SCORE using 6k elements from the alessandrasala79/ai-vs-human-generated-dataset dataset for training. After 0.8 F1-SCORE the marginal gain in precision seem to lower dramatically.  It may be possible to achieve a 0.85 to 90 F1-SCORE using this method by training on the complete dataset & ajusting RF parameters. 
