# State-space encoding applied on the video stream output system of the ball in box environment.

The code accompanying a upcoming paper. 

# Instructions

* Get anaconda 3 (python>= 3.6)
* Install pytorch ([Instructions](https://pytorch.org/get-started) CUDA optional)
* Install [deepSI](https://github.com/GerbenBeintema/deepSI) (our preliminary toolbox, version used `d4d21112325d10719fbb0a5561ef70c3bab87df8`)
  * `git clone git@github.com:GerbenBeintema/deepSI.git` 
  * `cd deepSI`
  * `pip install -e .`
* install jupyter notebook 
  * (i.e. `conda install -c conda-forge jupyterlab`)
* Use jupyter notebooks to open notebooks.
  * (e.g. `jupyter notebook ball-in-box-encoder-approach.ipynb`)

# State-space encoding structure

![encoder image](Encoder-graphic.png)