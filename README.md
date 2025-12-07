# SciTextures: Dataset of simulations and generative code for textures and visual-patterns generation
The SCITextures dataset is a large-scale collection of images featuring visual patterns and textures from a wide range of scientific and artistic domains, along with the corresponding models and generation code that produce them. The dataset spans over 1,270 distinct generative models, ranging from simple systems and mathematical functions, such as the Ising model and the Game of Life, to simulations of cities, materials, chemical reactions, biological growth, and many others. Each model is accompanied by standardized, flexible code that generates a given number of images at arbitrary resolutions, as well as 100 example images produced by the model. Most images are colored and seamlessly tileable, achieved through the use of periodic boundary conditions. In total, the dataset includes approximately 109,000 images. The dataset is available under CC0 license.

## [Documentation: SciTextures: Collecting and Connecting Visual Patterns, Models, and Code Across Science and Art](https://arxiv.org/pdf/2511.01817)

## Sources: [Zenodo](https://zenodo.org/records/17485502), [Hugging Face](https://huggingface.co/datasets/FlyingFrog/SciTextures)

# Downloads:

[Full dataset (jpg format) 1270 scripts and 109,000 images (12gb)](https://zenodo.org/records/17485502/files/Scitexture_Full_110K_images_jpg_format.zip?download=1)

[All scripts and a single sample image for each model (1270 scripts and images 174mb)](https://zenodo.org/records/17485502/files/Scitextures_Single_Sample_From_Each_Model_1270_Images_jpg.zip?download=1)

[All scripts no images (1270 simulations and models, 28mb)](https://zenodo.org/records/17485502/files/Scitextures_code_and_data_only.zip?download=1)

![](/Sample0.jpg)

## How to use code:

The code for each model is given in the datafolder.

The code structure of all models is the same:

All the code is contained in the file: generate.py

The code can be run using the function:  

def generate_texture(outdir: str, sz: int = 512, num_samples: int = 20):

outdir: output folder where the images will be saved.

sz: size of each image in pixels (across a single dimension)/

num_samples: number of different images to generate

# Evaluation scripts
Scripts for the evaluation tasks described in the [paper](https://arxiv.org/pdf/2511.01817) are available at: 

[Im2Im][https://github.com/sagieppel?tab=repositories](https://github.com/sagieppel/Im2Im-Test-VLM-ability-to-identify-images-formed-by-the-same-process), 
[Im2Code](https://github.com/sagieppel/Im2Code-Test-LVLMS-ability-to-associate-images-with-the-code-and-models-that-generate-them), 
[IM2SIM](https://github.com/sagieppel/Im2Sim-From-image-to-coding-the-simulation-of-the-physical-system-in-the-image-using-VLM)

# Generation Scripts 
Scripts used in the generation of the dataset available at:
[Collecting simulations and models standard](https://github.com/sagieppel/Collecting-models-and-code-for-Visual-patterns-and-textures-generation-using-Agentic-AI),

[Inferring simulation and models from images](https://github.com/sagieppel/Im2Sim-From-image-to-coding-the-simulation-of-the-physical-system-in-the-image-using-VLM)


![](/Sample5.jpg)
![](/Sample2.jpg)




