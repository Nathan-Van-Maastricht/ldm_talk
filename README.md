A talk summarising my work on a text condition latent diffusion model using a flow matching target.

The models in the talk were all trained from scratch.

1. An encoder/decoder was trained with a GAN setup, using l1, adversarial loss, and feature matching loss. The discriminator was trained with a hinge loss. No pretrained model was used for making the images sharper
2. A masked language model was trained and the embeddings were used for the text conditioning
3. A ViT was used for the actual diffusion model
