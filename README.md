# Segmentation: Simple Encoder-Decoder Architecture
[This is the Dataset](http://www.cardiacatlas.org/studies/sunnybrook-cardiac-data/)
Reference: Radau P, Lu Y, Connelly K, Paul G, Dick AJ, Wright GA. “Evaluation Framework for Algorithms Segmenting Short Axis Cardiac MRI.” The MIDAS Journal – Cardiac MR Left Ventricle Segmentation Challenge, http://hdl.handle.net/10380/3070

* The dataset is preprocessed and saved as pickle files in this repository. The code uses data from Google Drive which is what is uploaded here in this repository for your use.
* The environment is Python 3 and Keras 2. This was run on Google Colab with GPU runtime enabled.

The 'sunnybrrok_ecdc.ipynb' uses the encoder-decoder model with depth of 4 and trains the model with a batch size of 8. The training was done in phases for 25 epochs.
Please check out the [Medium Post: Automatic Segmentation of MRI Images](https://medium.com/@tirthankar.banerjee/automatic-segmentation-of-mri-images-2629eaf94071) for details.

