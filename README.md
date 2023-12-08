# MECH 501 - Final Project (Fall 2023)
**McGill University**

**Author:** David Brenken

---

## Instructions to Run Code:

**Step 1:** Create a Python virtual environment (.venv) of version 3.10.9 in this directory.

**Step 2:** Install dependencies with pip, ensuring the version is correct:

```bash
pip install matplotlib==3.8.2
pip install tensorflow==2.10.0
pip install pandas==2.1.3
pip install scipy==1.11.4
pip install scikit-learn==1.3.2
pip install tqdm==4.66.1

```
It is *extremely* important that the tensorflow version and python version are correct, or the code will not run.

## FILE DECOMPRESSION:

two directories are too large to directly host in github.

These are: ./Models and ./CNN_data/audio

The contents of ./Models contains the results of my models as well as pretrained models which may be run

The contents of ./CNN_data/audio are the .wav files from the original dataset. This is mandatory to generate the dataset

the dropbox link for both is provided here:

./Models.zip:

[download](https://www.dropbox.com/scl/fi/rmsx8o6h5xr275pbkq1i8/Models.zip?rlkey=m18fsm1yprw1u96y0buwde3yd&dl=0)

./CNN_data/audio:

[download](https://www.dropbox.com/scl/fi/7wmpcsratspawm37inn2d/audio.zip?rlkey=ualdm82ee1akkxgrimsuex4zr&dl=0)

Note that you must create the respective directories (i.e. ./Models and ./CNN_data/audio) when you unzip the files! If these paths are incorrect with respect to your python interpreter, the code will not run.
