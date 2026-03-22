Developed a text-to-speech model using Wavenet.

Algorithm Steps:
Input text
Convert text → phoneme sequence
Generate Mel spectrogram using Tacotron
Use WaveNet vocoder:
Predict audio sample step-by-step
Combine samples → waveform
Output speech
