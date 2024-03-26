## A study on emotives

The _Emotives Project_ is a set of tools, which allow you to build your own real-time emotion recognizer based on acoustic properties of speech and *not* that of word information.

This project is a companion to its [sister](https://github.com/samuncler/emotives-soundnet) project.

## Abstract

Automatic detection and interpretation of social signals carried by voice, gestures, mimics, etc. will play a key-role for next-generation interfaces as it paves the way towards a more intuitive and natural human-computer interaction. The paper at hand introduces Social Signal Interpretation (SSI), a framework for real-time recognition of social signals. SSI supports a large range of sensor devices, filter and feature algorithms, as well as, machine learning and pattern recognition tools. It encourages developers to add new components using SSI's C++ API, but also addresses front end users by offering an XML interface to build pipelines with a text editor. SSI is freely available under GPL at [open-ssi](http://openssi.net).

## Platform

Python

## Installation

With [Visual Studio 2015 Redistributable](https://www.microsoft.com/en-us/download/details.aspx?id=52685), run `install.cmd` to download core binaries and install an embedded version of Python.

If you plan to extract SoundNet features, you will also have to execute `install_tensorflow.cmd` and download the file [sound8.npy](https://drive.google.com/drive/folders/1zjNiuLgZ1cjCzF80P4mlYe4KSGGOFlta) into the `chains` folder.

For convenience, they are also found [here](https://drive.proton.me/urls/Z2GZEEEGVM#rZ1GwrADwlaV).

## Documentation

https://rawgit.com/hcmlab/emovoice/master/docs/index.html

## Credits
* [SSI](http://openssi.net) -- Social Signal Interpretation Framework
* [LIBSVM](https://www.csie.ntu.edu.tw/~cjlin/libsvm/) -- A Library for Support Vector Machines
* [LIBLINEAR](https://www.csie.ntu.edu.tw/~cjlin/liblinear/) -- A Library for Large Linear Classification
* [openSMILE](http://audeering.com/technology/opensmile/) -- The Munich Versatile and Fast Open-Source Audio Feature Extractor
* [Emo-DB](http://emodb.bilderbar.info/start.html) -- Berlin Database of Emotional Speech
* [SoundNet](https://github.com/eborboihuc/SoundNet-tensorflow) -- TensorFlow implementation of "[SoundNet](http://soundnet.csail.mit.edu/)"

## Reference

``` bibtex
@inproceedings{Wagner13,
 author = {Wagner, Johannes and Lingenfelser, Florian and Baur, Tobias and Damian, Ionut and Kistler, Felix and Andr{\'e}, Elisabeth},
 title = {The social signal interpretation (SSI) framework: multimodal signal processing and recognition in real-time},
 booktitle = {Proceedings of the 21st ACM international conference on Multimedia},
 series = {MM '13},
 year = {2013},
 isbn = {978-1-4503-2404-5},
 location = {Barcelona, Spain},
 pages = {831--834},
 numpages = {4},
 url = {http://doi.acm.org/10.1145/2502081.2502223},
 doi = {10.1145/2502081.2502223},
 acmid = {2502223},
 publisher = {ACM},
 address = {New York, NY, USA},
 keywords = {multimodal fusion, open source framework, real-time pattern recognition, social signal processing},
}
```
## License

The framework is released under LGPL (see LICENSE).
Please note custom license files for the plug-ins (see LICENSE.*).

##  Author

Johannes Wagner, Lab for Human Centered Multimedia, 2018
