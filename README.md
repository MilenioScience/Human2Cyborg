# Human2Cyborg
I try to create GAN's model for image-image translation of human face photo to cyborg face photo

For this problem because deep learning GAN such as CylceGAN and UGATIT need lot of data image for model to be able have good learning, i use DCGAN to generate cyborg image photo, but unfortunately the image generation by model dont have variety

Image-image translation use CycleGAN and UGATIT.

Result of CycleGAN is good enough but the model only change the skin color to blue and pale but can't do shape transformation such as ear cyborg, line skin cyborg, etc.

Result of UGATIT is like that because i only train using epoch=1, because i dont have powerfull gpu, so if you want to train UGATIT please use powerful gpu, minimum 24gb, and you must have a lot of storage in your computer.

Here is each trained model that you can use as pre trained model.

Trained generator model : https://drive.google.com/drive/folders/1WjtBHBSm5w4eRZR2gcQnndAxTeM1WGRz?usp=share_link
Trained CycleGAN image-image translation : https://drive.google.com/drive/folders/1l7GDvi1matFnntRe7M1_AazJoOVBoFfT?usp=share_link
