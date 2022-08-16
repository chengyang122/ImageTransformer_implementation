# ImageTransformer_implementation

This is an implementation of [ImageTransformer](https://arxiv.org/abs/1802.05751)
This is a practice of transformer model. There are several ways of using transformer in computer vision. 
One important difficulty they need to conquer is the size of the model. Image transformer choose to predict the next 
pixal with limited previous pixals. However vision transformer choose to predict the next pixal by summary previous pixals into a patch.
The information contained in one pixal is too trivial. So [An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale](https://arxiv.org/abs/2010.11929)
is better.
