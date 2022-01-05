Presented here are some samples from the [original demo site](https://thuhcsi.github.io/icassp2022-cross-speaker-style-transfer) of our paper, as well as their quality-improved version.
- The original audios suffers from the buzz noise that comes along with the waveform reconstruction process.
- By resorting to a better optimized vocoder, we manage to improve the quality of the generated speech, so that listeners would be less disturbed by factors that are irrelevant to our model. 

| Proposed + Original Vocoder | Proposed + Improved Vocoder |
|:----------------------------|:----------------------------|
|<audio controls><source src="./static/c.wav" type="audio/wav">Your browser does not support the audio element.</audio>|<audio controls><source src="./static/c_improved.wav" type="audio/wav">Your browser does not support the audio element.</audio>|
|<audio controls><source src="./static/b.wav" type="audio/wav">Your browser does not support the audio element.</audio>|<audio controls><source src="./static/b_improved.wav" type="audio/wav">Your browser does not support the audio element.</audio>|
|<audio controls><source src="./static/a.wav" type="audio/wav">Your browser does not support the audio element.</audio>|<audio controls><source src="./static/a_improved.wav" type="audio/wav">Your browser does not support the audio element.</audio>|
