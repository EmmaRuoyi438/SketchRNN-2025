# SketchRNN-2025
An updated implementation of Google Magenta's SketchRNN model for training and sampling vector-based sketches using custom datasets. 

This demo uses **KanjiVG** dataset (http://kanjivg.tagaini.net/). 

Current demo includes: 
- Unconditional generation (encode/decode from latent space) 
- Latent space interpolation between sketches 
- Custom SVG dataset conversion to stroke-3 format and .npz file for training

This project adapts TensorFlow 1.x code to run in a modern TensorFlow 2.x environment with v1 compatibility mode enabled.

## Demo Features

- Trained model: KanjiVG vector character set
- Framework: TensorFlow 2.x (with `tf.compat.v1`)
- Platform: Kaggle notebook
- Output: SVG sketches
