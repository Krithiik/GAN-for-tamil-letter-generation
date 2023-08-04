# GAN-for-tamil-letter-generation
DCGAN for image generation
In recent years, Generative Adversarial Networks (GANs) have shown remarkable success in
generating realistic images, videos, and even text. In this project, I explored the application of DCGAN (Deep Convolutional Generative Adversarial Network) in generating Tamil letters.
Tamil is a classical language with a rich literary tradition, and its script is complex, making it a challenging task for GANs. We address this challenge by using DCGAN architecture that
takes into account the unique characteristics of Tamil letters.

GANs are made of two distinct models, a generator and a discriminator. The job of the generator is to spawn ‘fake’ images that look like the training images. The job of the discriminator is to look at an image and output whether or not it is a real training image or a fake image from the generator. During training, the generator is constantly trying to outsmart the discriminator by generating better and better fakes, while the discriminator is working to become a better detective and correctly classify the real and fake images. The equilibrium of this game is when the generator is generating perfect fakes that look as if they came directly from the training data, and the discriminator is left to always guess at 50% confidence that the generator output is real or fake.

A DCGAN is a direct extension of the GAN described above, except that it explicitly uses
convolutional and convolutional-transpose layers in the discriminator and generator,
respectively.

I used the Mepco Tamil Printed Characters dataset to train the generator and the discriminator. The generator will generate Tamil character resembling the dataset. It consists of 504 images of each 'uyir eluthukkal' in tamil to a total of 6,552 character images.
