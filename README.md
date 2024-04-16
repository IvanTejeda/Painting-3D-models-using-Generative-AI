# Painting-3D-models-using-Generative-AI

Hi, this is a project I did in the spring semester of 2024.

I leveraged generative AI models to paing 3D models. 

I used Google Colab, PyTorch3D, Stable Diffusion, and ControlNet from HuggingFace to perfom the following tasks:
Rendered a 3D mesh of a cow with it's texture
<ul>
    <li>Rendered a 3D mesh of a cow with its texture.</li>
    <li>Replaced the cow's texture with a different PNG image.</li>
    <li>Given prompt and texture image as inputs, generated new texture images using Stable Diffusion and ControlNet from HuggingFace.</li>
    <li>Rendered the 3D mesh of the cow with the AI-generated texture images.</li>
    <li>Used ControlNet with prompt and 2D rendered images as inputs, instead of prompt and texture image. This led to better AI-generated images.</li>
    <li>Developed algorithm to paint 3D object given AI-generated 2D image from the last step.</li>
</ul>

Check out the source code for the results!
