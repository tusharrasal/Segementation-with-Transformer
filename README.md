# Segementation-with-Transformer
SegFormer (b0-sized) model fine-tuned on ADE20k
SegFormer model fine-tuned on ADE20k at resolution 512x512. It was introduced in the paper SegFormer: Simple and Efficient Design for Semantic Segmentation with Transformers by Xie et al. and first released in this repository.


Model description
SegFormer consists of a hierarchical Transformer encoder and a lightweight all-MLP decode head to achieve great results on semantic segmentation benchmarks such as ADE20K and Cityscapes. The hierarchical Transformer is first pre-trained on ImageNet-1k, after which a decode head is added and fine-tuned altogether on a downstream dataset.
