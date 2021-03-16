# Data structure

Data was preprocessed using two "anchor points" to ensure cough sounds were framed consistently.
* **Anchor point 1**: Max RMS energy used to place a 460 ms window around a manually-segmented cough sound. These files are in the directories non, hand, and elbow. 
* **Anchor point 2**: Normalised RMS energy used to place identify a start and end to a cough sound.These files are in the directories none_short, hand_short, and elbow_short.

The naming format is "id-gender-etiquette-number.wav", e.g. 13-f-e-07.wav
* id: unique identifier for each participant
* gender: m - male, f - female, o - other
* etiquette: n - none, h - hand, e - elbow
* number: number of cough from participant
