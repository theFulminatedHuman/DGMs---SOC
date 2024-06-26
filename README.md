# DGMs---SOC
DGMS (Deep Generative Models) is my SOC project at IITB. We will learn and implement DCGANs, VAEs, Stable Diffusion on various datasets. I have already tried implementing CelebsA dataset on DCGAN (I tried that with only 500 input images).
I have attached the notebook and pdf to that in the repo. The result I got was not that good as I expected it to be mostly because of the limited GPU on the colab. The Generator and Discriminator losses were taking lot of epochs to converge (>1000).
Here are some of the results that I got:
![Screenshot 2024-06-18 095423](https://github.com/theFulminatedHuman/DGMs---SOC/assets/98097564/52f553b2-8ac3-4d7b-88b4-490153b6ddaa) 
![Screenshot 2024-06-18 150631](https://github.com/theFulminatedHuman/DGMs---SOC/assets/98097564/185e454f-9eed-4c64-bb2a-74687f65cfe2)
![Screenshot 2024-06-18 233809](https://github.com/theFulminatedHuman/DGMs---SOC/assets/98097564/2324511e-9874-48d5-acc0-1c8093bc9dff)
The fluidity in faces at the last image is mostly because of overfitting. 



My this week target is to implement VAEs on the dataset. 
