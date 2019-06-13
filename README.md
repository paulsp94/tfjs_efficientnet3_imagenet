# EfficientNet-B3 in tfjs

EfficientNet-B3 model pretrained on Imagenet dataset converted into tfjs.  
Original model and weights from https://github.com/qubvel/efficientnet.

Doesn't currently work, because it doesn't find the required Initializers in tfjs.

Todo:  
 - [ ] Implement EfficientConv2DKernelInitializer
 - [ ] Implement EfficientDenseKernelInitializer
