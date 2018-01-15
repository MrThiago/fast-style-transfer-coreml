# Fast Style Transfer, CoreML, TensorFlow

Create an iOS app — like Prisma — with CoreML, Fast Style Transfer, and TensorFlow.

<p align="center">
  <img src="https://github.com/mdramos/fast-style-transfer-coreml/blob/master/assets/banner.jpg?raw=true" width="700"/>
</p>

## Installation
```bash
git clone https://github.com/mdramos/fast-style-transfer-coreml.git
```

## Dependencies

* Xcode 9
* Python 2.7
* TensorFlow (1.0.0 works best with fast-style-transfer, and 1.1.0 or greater for tf-coreml)
* Fast Style Transfer: https://github.com/lengstrom/fast-style-transfer
* TensforFlow-CoreML: https://github.com/tf-coreml/tf-coreml

Note that you'll want to make the necessary adjustments for Fast-Style-Transfer and TensorFlow-CoreML. I write about these in [my medium article](https://medium.com/@rambossa/diy-prisma-fast-style-transfer-app-with-coreml-and-tensorflow-817c3b90dacd). The adjusments are also available in this repo: [fst](https://github.com/mdramos/fast-style-transfer-coreml/tree/master/fast_style_transfer) and [tf-coreml](https://github.com/tf-coreml/tf-coreml).

## Models 
You can train your own models using FST, and use my adjustments to convert them to CoreML models. I've already converted the pre-trained models from FST:

CoreML Models: https://drive.google.com/drive/folders/1CBSanBHbXC5-bJNTTk3-r1WSq56z0eKG?usp=sharing

## iOS

Once you have your models, just import them into the Xcode project. The current setup looks for a particular set of models (wave, udnie, rain_princess, and la_muse)


## License
Copyright (c) 2018 Michael Ramos.
MIT on any of my code, but you'll need to abide by the Licences of the libraries used (FST, tf-coreml)
