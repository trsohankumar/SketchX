# SketchX: Sketch to image transformation using generative adverserial networks
## Abstract
This project aims to develop a model that 
can convert sketches into portraits of Indian people using deep image-to-image translation 
techniques. Converting a sketch into a portrait photo is done by implementing a pix2pix 
approach to conditional GANs, with the generator following a U-net architecture and the 
discriminator a PatchGAN. The system is trained on a dataset containing faces of Indian 
people, ensuring that the generated image will also be of Indian origin. The results are 
evaluated based on the Fréchet Inception Distance between the real and generated image.

## Results of the model

![image](https://github.com/trsohankumar/SketchX/assets/63629207/c21eb33a-1fde-4c3b-b338-5faf8d3211e7)

## FID Score
![image](https://github.com/trsohankumar/SketchX/assets/63629207/fbedd7cd-228f-41bd-a981-ceedc1730a19)
