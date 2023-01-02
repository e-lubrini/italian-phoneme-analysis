# italian-phoneme-analysis

## Recording
Software: Audacity 3.0.0

Hardware: Dell Latitude 5490 integrated microphone

3 file recordings: standing, sitting, lying down.

## Annotation
Software: Praat

Two tiers: orthographic and phonetic (SAMPA) transcription.

## Data Collection
Software: Praat, [get_formants_for_vowels.praat script](https://github.com/sbuss/get-formants-for-vowels/blob/master/get_formants_for_vowels.praat)

3 txt files (one per recording) containing 3 formants of each phoneme

## Data Analysis
Software: Jupyter Lab

Python 3.9.2

Visual analysis of changes in the formants when changing position.

### Data Visualisation
#### First Formant

<p float="center">
  <img src="https://github.com/e-lubrini/italian-corpus/blob/main/data%20analysis/f1.png" width="500" />
</p>

#### Second Formant

<p float="center">
  <img src="https://github.com/e-lubrini/italian-corpus/blob/main/data%20analysis/f2.png" width="500" />
</p>

#### Third Formant

<p float="center">
  <img src="https://github.com/e-lubrini/italian-corpus/blob/main/data%20analysis/f3.png" width="500" />
</p>

### Observations
The corpus is too small to claim that any generalisation derived from its analysis is accurate without any contextual prior knowledge of formant variation.
However, various studies have already discussed the effect of body position on formants. The results from this corpus seem to confirm a higher F1 frequency for the vowel /i/ in the supine position, as already reported by Vorperian (2015) and, just as reported in the same study, F1 and F2 frequencies for the vowels /i/ and /a/ showed no significant differences were observed between vowels produced in upright versus supine positions.

### References
Vorperian, H. K., Kurtzweil, S. L., Fourakis, M., Kent, R. D., Tillman, K. K., & Austin, D. (2015). Effect of body position on vocal tract acoustics: Acoustic pharyngometry and vowel formants. The Journal of the Acoustical Society of America, 138(2), 833–845. https://doi.org/10.1121/1.4926563
