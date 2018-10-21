# LSTM + CTC + Tensorflow Example

This model does currently not work!

## Installation
```
# on mac
pip install pillow
pip install opencv-python
brew install cmake
brew tap homebrew/science
brew install opencv
sh ./prepare_train_data.sh
```

```
# on ubuntu
pip intall pillow
pip install opencv-python
pip install tensorflow-gpu
```


The `prepare_train_data.sh` script would download the [SUN database](http://vision.princeton.edu/projects/2010/SUN/SUN397.tar.gz) and extract the pitures to bgs dir. Then you can run `python gen.py` to generate test and train dir.

When the train and test data set are ready you can start the train process by `nohup python lstm_and_ctc_ocr_train.py `.

## Requirements

- Python 2.7+ / Python 3.5+
- Tensorflow 1.0+

##
## License

This project is licensed under the terms of the MIT license.

See README for more information.
