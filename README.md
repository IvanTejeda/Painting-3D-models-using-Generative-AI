# Painting-3D-models-using-Generative-AI

Hi, this is a project I did in the spring semester of 2024.

I leveraged generative AI models to paint 3D models. 

I used Google Colab, PyTorch3D, Stable Diffusion, and ControlNet from HuggingFace to perform the following tasks:

- **Rendered a 3D mesh of a cow with its texture.**
- **Replaced the cow's texture with a different PNG image.**
- **Given prompt and texture image as inputs, generated new texture images using Stable Diffusion and ControlNet from HuggingFace.**
- **Rendered the 3D mesh of the cow with the AI-generated texture images.**
- **Used ControlNet with prompt and 2D rendered images as inputs, instead of prompt and texture image. This led to better AI-generated images.**
- **Developed algorithm to paint 3D object given AI-generated 2D image from the last step.**

Check out the source code for the results!
