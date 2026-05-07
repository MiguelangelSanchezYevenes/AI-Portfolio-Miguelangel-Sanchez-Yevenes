
## Problem Statement

The main problem in this project was understanding how diffusion models generate images from random noise. The goal was to learn how AI systems can gradually remove noise step-by-step until a recognizable image is created.

## Approach and methodology

The project used a diffusion model with a U-Net architecture. . The process started by adding noise slowly to images until they became fully random and during training, the model learned how to reverse this process by predicting and removing noise step-by-step. The model also used embeddings and one-hot vectors to tell the AI which digit to generate.

## Results and evaluation

The results showed that the model improved as training continued. At first, the generated images looked like random noise, but over time the images became clearer and recognizable. CLIP scores were used to evaluate how closely the generated images matched the intended digit labels. Simpler digits such as 0 and 1 were easier for the model to generate. But as they increase, it was harder since their curves.

## Your learning outcomes

I learned: 

How diffusion models work

Why gradual noise removal is important in AI image generation

Real-world applications of diffusion models, including AI art generation and content creation
