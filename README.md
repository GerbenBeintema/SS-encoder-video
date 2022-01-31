# State-space encoding applied on the video stream output system of the ball in box environment.

The code accompanying a published paper. [link](https://www.sciencedirect.com/science/article/pii/S2405896321012167)

```
@article{beintema2021non,
  title={Non-linear state-space model identification from video data using deep encoders},
  author={Beintema, Gerben I and Toth, Roland and Schoukens, Maarten},
  journal={IFAC-PapersOnLine},
  volume={54},
  number={7},
  pages={697--701},
  year={2021},
  publisher={Elsevier}
}
```

The code here has been updated to be compediable with the newest version of deepSI (0.3.0). The exact version used in the paper can be found at `7f375bf4013e294779bebbee28687cb66c45a23d` for this repository and `0216a6fe9f86d93fb1296de71af2289295dae1bf` in deepSI. 


# Instructions

* Get anaconda 3 (python>= 3.6)
* Install pytorch ([Instructions](https://pytorch.org/get-started) CUDA optional)
* Install [deepSI](https://github.com/GerbenBeintema/deepSI)
  * `git clone git@github.com:GerbenBeintema/deepSI.git` 
  * `cd deepSI`
  * `pip install -e .`
* install jupyter notebook 
  * (i.e. `conda install -c conda-forge jupyterlab`)
* Use jupyter notebooks to open notebooks.
  * (e.g. `jupyter notebook ball-in-box-encoder-approach.ipynb`)

# State-space encoding structure

![encoder image](Encoder-graphic.png)
