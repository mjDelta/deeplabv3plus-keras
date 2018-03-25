## Deeplab v3+ in keras
DeepLab is a state-of-art deep learning model for semantic image segmentation. For tensorflow implemention, please refer to [tensorflow/models/research]: https://github.com/tensorflow/models/tree/master/research/deeplab
</br>

#### The Features of DeepLab v3+
* Encoder-Decoder Structures
* Atrous Convolutions in ASPP structure
* Separable Convolutions instead of traditional Convolutions
* Bilinear Interpolation instead of Transpose Convolutions

#### The Brief Structure 
> Encoder
1. Xception as the Feature Extractor
2. ASPP
3. Separable Convolutions
>

> Decoder
1. Upsampling
2. Separable Convolutions
>