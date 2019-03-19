# Image Similarity Search with Deep Learning


This repo is a large sample of the coursework in the [Zero to Deep Learning Bootcamp](https://bootcamp.zerotodeeplearning.com). The Bootcamp is a hands-on and immersive course to learn Machine Learning & Deep Learning fast with Python, Pandas, Matplotlib, Scikit-Learn, Keras and Tensorflow.

## Next Bootcamps: 25-29 March, SF Bay area . [Register here](https://bootcamp.zerotodeeplearning.com)

## Quick start guide

#### Download and install Anaconda or Miniconda Python 3

Download Anaconda here: https://www.anaconda.com/download or download Miniconda here: https://docs.conda.io/en/latest/miniconda.html and then install it on your system.

#### Open a terminal

#### Clone this repository on your local computer
```
git clone https://github.com/zerotodeepearning/deep_learning_image_similarity.git
```

#### Change to course folder
```
cd deep_learning_image_similarity
```

#### Create Conda environment

We provide an [environment configuration file](environment.yml) with all the required dependencies.

```
conda env create
```

wait for the environment to create, this may take a few minutes. Note that this environment is based on Python 3.6 because Tensorflow does not support Python 3.7 yet.

#### Activate the environment (Mac/Linux)
```
conda activate image_similarity
```

#### Activate the environment (Windows)
```
activate image_similarity
```

Check that your prompt changed to

```
(image_similarity) $
```

Now you can run jupyter notebook from within the environment.

#### Launch Jupyter Notebook
```
jupyter notebook
```
and access it from your browser at: http://localhost:8888

You are good to go! Enjoy!


### Troubleshooting

#### Updating Conda

If you have installed Anaconda a long time ago, you may want to update it by running:
```
conda update conda
```
and then:
```
conda update anaconda
```

#### Deactivating the environment (Mac/Linux)
```
conda deactivate
```

#### Deactivating the environment (Windows)
```
deactivate
```

#### Deleting the environment
If you decide to completely delete the environment from your system you should use the following command:
```
conda remove -y -n image_similarity --all
```
