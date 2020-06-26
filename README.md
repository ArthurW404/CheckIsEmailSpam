# Check Spam
A ML model to identify emails are spam or not, supervised machine learning (Classification) is used.

### results
Models used from scikit-learn includes random forest Classifier and decision tree, which are getting 92 - 93% accuracy in detecting spam. However false positives (Email which is not spam being labelled as spam) are quite high.
Neural network were also used (Multi-layer perceptron (MLP) algorithm) with lower accuracy most likely due to poor calibration of the MLPclassifier.


### How to use:

##### To run:
1. Open jupyter notebook
2. Click on the checkSpam.ipynb file
3. Under the kernal dropdown, click restart & run all

#### Checking email input is spam
##### Method 1: Using input.txt
1. Open input.txt file and paste email into the file
2. Run checkSpam.ipynb file, results can be found at the bottom

##### Method2: Doing it in .ipynb file
1. Click on the checkSpam.ipynb file 
2. Scroll to bottom of page, replace email variable docstring with the email which needs to be checked 
3. run file, results can be found at the bottom

### Dataset:
https://archive.ics.uci.edu/ml/datasets/Spambase

### dependencies:
  - _libgcc_mutex=0.1=main
  - attrs=19.3.0=py_0
  - backcall=0.1.0=py36_0
  - blas=1.0=mkl
  - bleach=3.1.4=py_0
  - ca-certificates=2020.1.1=0
  - certifi=2020.4.5.1=py36_0
  - cycler=0.10.0=py36_0
  - dbus=1.13.14=hb2f20db_0
  - decorator=4.4.2=py_0
  - defusedxml=0.6.0=py_0
  - entrypoints=0.3=py36_0
  - expat=2.2.6=he6710b0_0
  - fontconfig=2.13.0=h9420a91_0
  - freetype=2.9.1=h8a8886c_1
  - glib=2.63.1=h5a9c865_0
  - gmp=6.1.2=h6c8ec71_1
  - gst-plugins-base=1.14.0=hbbd80ab_1
  - gstreamer=1.14.0=hb453b48_1
  - icu=58.2=he6710b0_3
  - importlib-metadata=1.6.0=py36_0
  - importlib_metadata=1.6.0=0
  - intel-openmp=2020.1=217
  - ipykernel=5.1.4=py36h39e3cac_0
  - ipython=7.13.0=py36h5ca1d4c_0
  - ipython_genutils=0.2.0=py36_0
  - ipywidgets=7.5.1=py_0
  - jedi=0.17.0=py36_0
  - jinja2=2.11.2=py_0
  - joblib=0.15.1=py_0
  - jpeg=9b=h024ee3a_2
  - jsonschema=3.2.0=py36_0
  - jupyter=1.0.0=py36_7
  - jupyter_client=6.1.3=py_0
  - jupyter_console=6.1.0=py_0
  - jupyter_core=4.6.3=py36_0
  - kiwisolver=1.2.0=py36hfd86e86_0
  - libedit=3.1.20181209=hc058e9b_0
  - libffi=3.2.1=hd88cf55_4
  - libgcc-ng=9.1.0=hdf63c60_0
  - libgfortran-ng=7.3.0=hdf63c60_0
  - libpng=1.6.37=hbc83047_0
  - libsodium=1.0.16=h1bed415_0
  - libstdcxx-ng=9.1.0=hdf63c60_0
  - libuuid=1.0.3=h1bed415_2
  - libxcb=1.13=h1bed415_1
  - libxml2=2.9.9=hea5a465_1
  - markupsafe=1.1.1=py36h7b6447c_0
  - matplotlib=3.1.1=py36h5429711_0
  - mistune=0.8.4=py36h7b6447c_0
  - mkl=2020.1=217
  - mkl-service=2.3.0=py36he904b0f_0
  - nbconvert=5.6.1=py36_0
  - nbformat=5.0.6=py_0
  - ncurses=6.2=he6710b0_1
  - notebook=6.0.3=py36_0
  - numpy=1.14.2=py36hdbf6ddf_0
  - openssl=1.1.1g=h7b6447c_0
  - pandas=0.25.3=py36he6710b0_0
  - pandoc=2.2.3.2=0
  - pandocfilters=1.4.2=py36_1
  - parso=0.7.0=py_0
  - pcre=8.43=he6710b0_0
  - pexpect=4.8.0=py36_0
  - pickleshare=0.7.5=py36_0
  - pip=20.0.2=py36_3
  - prometheus_client=0.7.1=py_0
  - prompt-toolkit=3.0.5=py_0
  - prompt_toolkit=3.0.5=0
  - ptyprocess=0.6.0=py36_0
  - pygments=2.6.1=py_0
  - pyparsing=2.4.7=py_0
  - pyqt=5.9.2=py36h05f1152_2
  - pyrsistent=0.16.0=py36h7b6447c_0
  - python=3.6.9=h265db76_0
  - python-dateutil=2.8.1=py_0
  - pytz=2020.1=py_0
  - pyzmq=18.1.1=py36he6710b0_0
  - qt=5.9.7=h5867ecd_1
  - qtconsole=4.7.4=py_0
  - qtpy=1.9.0=py_0
  - readline=7.0=h7b6447c_5
  - scikit-learn=0.21.1=py36hd81dba3_0
  - scipy=1.3.2=py36h7c811a0_0
  - send2trash=1.5.0=py36_0
  - setuptools=47.1.1=py36_0
  - sip=4.19.8=py36hf484d3e_0
  - six=1.15.0=py_0
  - sqlite=3.31.1=h62c20be_1
  - terminado=0.8.3=py36_0
  - testpath=0.4.4=py_0
  - tk=8.6.8=hbc83047_0
  - tornado=6.0.4=py36h7b6447c_1
  - traitlets=4.3.3=py36_0
  - wcwidth=0.1.9=py_0
  - webencodings=0.5.1=py36_1
  - wheel=0.34.2=py36_0
  - widgetsnbextension=3.5.1=py36_0
  - xz=5.2.5=h7b6447c_0
  - zeromq=4.3.1=he6710b0_3
  - zipp=3.1.0=py_0
  - zlib=1.2.11=h7b6447c_3

