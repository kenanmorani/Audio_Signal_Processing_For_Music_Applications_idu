# Audio Signal Processing for Music Applications_idu
* The codes are solutions to assignments given during the course dilevered by Prof. Baris Bozkurt.
* The codes include in depth audio analysis to audio data of coughing and sneezing wave sounds, recorded voices of me saying different letters, and manually annotated sound data.

# The codes:
### 'Feature Exctraction' folder
* The following code checks wave sound files of two different categories, cough and sneez. COugh and sneez files exist in the 'data' folder above.
* The code works on features extraction for the chosen wave sounds of coughs and sneezes. The chosen features the features extracted from the wave files include the amplitude frequency, spectrogram, Mel-frequency cepstral coeffecients and energy band ratio.
* The code includes results-clearfying comments in a general sense.

### 'Audio_Analysis_on_my_voice' folder
* The codes use my voice as data. Three wave sounds were recorded of me saying three different letters 'a', 'e', and 'o'. The voice files are in 'data' folder, 'kenansounds'.
* The code implements Windowing, Formants, and Convertion to midi chromagram to all three wave sounds. Comments on the results are in the code.

### 'Pitch Exctraction' folder
* The code uses the standard 'orchset'. The dataset cab be downloaded from https://zenodo.org/record/1289786#.YKqUs6IzZH5.
* The code collects ground truth values from the satndard data.
* The code makes prediction using Essentia-Melodia and Crepe Algorithms and check the prediction results in terms of Voicing Recall, Voicing False Alarm, Raw Pitch Accuracy, Raw Chroma Accuracy, and over all accuracy.
*   Comments on the performance of the two algorithms are at the end.
