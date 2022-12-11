[ AE FOR CREDIT ]

- Make sure that your gif and all other cell outputs are present in your notebook!

- Confirm that the digits are able to be reconstructed in the bottleneck
   - Make a few notes below talking about whether or not this is interesting and/or useful.
   
The TSNE projection and autoencoder gave out some similar output, except couple of specific classes. But for others, the outputs are highly similar.

- Confirm that the latent encoding's decomposition roughly matches with original data's.
   - Comment a bit on it. Is this a good sign? Does it have any use?
   
 From this phenomenon, I believe that the autoencoder can encode the relative positions by a shallow layer-strcture.


[ VAE FOR CREDIT ]

- Make sure both of your gifs are present in the notebook!

- Talk about a potential application that you think it would be cool to applied VAEs to.

VAEs can generate hand-written characters from typed one. And it can also be used to generate art works based on different bases and requirements. One of the examples can be cited below:
https://magenta.tensorflow.org/music-vae

[ GAN FOR CREDIT | BONUS ]

- Make sure that your gif and all other cell outputs are present in your notebook!

- Discuss a bit about the pros and cons of using a GAN in this context. 

Advantage: Numerous data output and enough model complexity. The generated image and the input image are highly similar.

Disadvantage: Long train time and large scale data usage.

- For 2470 students, the above will give you half of the bonus points. The other half can be obtained by trying out the WGAN-GP model below. 
