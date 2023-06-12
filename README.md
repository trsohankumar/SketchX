# SketchX: Sketch to image transformation using generative adverserial networks
## Abstract
This project aims to develop a model that 
can convert sketches into portraits of Indian people using deep image-to-image translation 
techniques. Converting a sketch into a portrait photo is done by implementing a pix2pix 
approach to conditional GANs, with the generator following a U-net architecture and the 
discriminator a PatchGAN. The system is trained on a dataset containing faces of Indian 
people, ensuring that the generated image will also be of Indian origin. The results are 
evaluated based on the Fréchet Inception Distance between the real and generated image.
