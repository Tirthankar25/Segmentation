# Segmentation: Simple Encoder-Decoder Architecture
Dataset: https://medium.com/r/?url=http%3A%2F%2Fwww.cardiacatlas.org%2Fstudies%2Fsunnybrook-cardiac-data%2F

* The dataset is preprocessed and saved as pickle files in this repository. Use that instead of that shown in the code. The code uses data from Google Drive which is what is uploaded here.
* The environment is Python 3 and Keras 2. This was run on Google Colab with GPU runtime enabled.

The 'sunnybrrok_ecdc.ipynb' uses the encoder-decoder model with depth of 4 and trains the model with a batch size of 8. The training was done in phases for 25 epochs.
Please check out the [Medium Post](https://medium.com/@tirthankar.banerjee/automatic-segmentation-of-mri-images-2629eaf94071) for details.

