# About
This project explores using KSVD to transcribe piano music in the time domain. See the paper in the `paper` directory for full details.

# Usage
The MAESTRO dataset is available [here](https://magenta.tensorflow.org/datasets/maestro) to get the training data. The code is located in the jupyter notebook `KSVD.ipynb`. The code is written in Julia and is pretty straightforward. One hiccup is that the code uses librosa (from Python) via `pyimport`. In order to do this, the `LLVM` versions of python and Julia must match. Using Python 3.7.1 and Julia 1.4 dev this works fine.
