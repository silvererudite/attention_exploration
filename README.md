# Exploring the wonderful world of attention

This repo features a series of interesting experiments with attention modules.  

## Image feature aggregation with Attention


In the notebook [Attention on images](apply_attention_to_image.md). I demonstrated a use case of feature aggregation using the concept of attention to images.
I utilized pretrained CLIP embeddings which already have knowledge of images. 

**Self-Attention Mechanism**:

When we apply self-attention to the CLIP embeddings (or the tokens we created from them), we're essentially allowing each part of the embedding to interact with every other part. This process can be seen as a form of feature aggregation.

**Multi-head Attention mechanism**:

The multi head attention mechanism basically extends the idea of self-attention by allowing multiple different aggregations to occur in parallel. We can think of it as what the entire image is composed of semantically or a semantic summary of the image.
