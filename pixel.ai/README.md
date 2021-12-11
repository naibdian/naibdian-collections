# Naibdian Pixel.AI Generator

Pixel.AI

Don't stop at basic snapshot, Pixel.AI is a unique artistic and scientific experiment combining generative art in NFT with live training AI.

WARNING: 
- GPU MANDATORY (uses <2GB of RAM). SHOULD NOT RUN ON MOBILE or your battery won't last.
- Basic pixellised shapes are both a self-limitation to simplify the problem to run on "normal" computer and also a choice of style because I love pixel art.

This experiment aims at:

- Training a real generative AI model in your browser and let it be a very unique NFT both visually and technically and let you get aware how AI learns along time.
- Showing how AI learning can be evocative & didactic. You'll wonder a lot about it and also about your own way of learning.
- Allowing people to share snapshots of their training AI and maybe build common galleries all together.


Process:

1. After load, it generates 9 unique random different pixel shapes (with rarities) based on towns, texts, geometry and noise (don't search any link between elements, any weird association is not wanted).
2. You launch the training and the model learns to deconstruct/reconstruct those 9 images from scratch. In fact, it generates a lot of hallucinatory images more or less inspired by them.
3. The training runs forever and displays its progress in a tile mosaic of random generations.
4. You watch it evolve, learn and forget too and I promise you'll see cool evocative pixel-art scenes.

Controls:
- H: hide/show help.
- Double-Click - Space: start/pause training.
- Q/A - D: Less or more tiles in mosaic (min 1).
- S - W/Z: Slower or faster tile refresh (min 0.5/sec).
- I: hide/show training stats. Click on it for panels (Loss, tiles, GPU, FPS).

Perks:
- Features mirror sprite rarity (some being very rare), texts, towns and rare mix makes higher difficulty for AI model.
- In Help, you'll see the feature "export" which allows to save trained model on your computer (4 files).
- If I see any interest from minters in it, I might deliver a new NFT (cheap) to display tiles built on those trained models.
- I'd like people to exchange snapshots of their training AI and share it to build (to me at least)
- This NFT might open new fields of artistic & scientific explorations to me.

Training details:
- First artefacts appear after 30sec-1min.
- Then basic shapes and colors should start to appears.
- Then lots of cool hallucinations with more and more complex shapes.
- Texts can take time to become visible (10-20min).
- GAN models generally converge and more and more imitate original images but it can also collapse into a full delirium tremens (which can be cool too).
- Each run is non deterministic (I've chosen that feature) so you should see different models at each run.

For the tech courageous, the model used here is a quite complex but cool Deep Learning model called "VAE-GAN". You just need to know that it consists in 2 models. One, the generator learns to decompose and reconstruct images. The other, the discriminator tries to identify true and generated images. But the generator also learns to trick the discriminator. And the generator has hidden super-powers using Math on steroids tricks to learn to decompose images in a "well-structured" and not too "messy" way You can find many articles about it but it's not simple in general.

Pixel.AI by @naibdian 2021
