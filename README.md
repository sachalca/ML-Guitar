# Guitar Chord Predictor

This project uses machine learning to predict the next guitar chord in a sequence, based on two or more input chords. The goal is to help compose musically coherent progressions that can be used to generate verses or full songs.

The dataset is based on songs from the late 1950s to early 1990s that appeared on the Billboard Hot 100. This era was chosen because the guitar was a dominant instrument in popular music at the time. The dataset reflects conventional chord progressions from widely known songs, which may not generalize perfectly to experimental or modern genres.

The model combines a GRU (Gated Recurrent Unit) for sequence learning, K-Means clustering for grouping similar chord patterns, and a Random Forest Classifier for final prediction. The code is written in Python and runs in a Jupyter notebook.

To use this project, open the notebook, run all cells, and provide a sequence of three chords as input. The model will return the most likely next chord or chords in the sequence. 
You can choose how many predicted chords you want to receive using the `n` parameter. Additionally, you can enable an option to avoid repeating any of the input chords by setting `avoid_repetition=True`. 
This makes the output more diverse and musically interesting when generating longer sequences.

This project is intended as a creative tool to assist musicians and composers. It is not meant to replace the creative process, but to support it by suggesting musically appropriate chord transitions based on past patterns.

Author: Sacha Le Clainff Alonzo  
