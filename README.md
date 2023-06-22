## Programming assignments and quizzes from all courses in the Coursera [Generative adversarial specialization](https://www.coursera.org/specializations/generative-adversarial-networks-gans) offered by `deeplearning.ai`.

-----

## Course 1

1. Generative model vs Discrimentative model

2. Activation and Common activations

3. Batch, padding, pooling, upsampling, convolution and transposed convolution operations.

4. Collapse mode, the generative model will produce sample of only one class. 

5. To solve the collapse mode problem new loss functions has been announces and we change BCE loss function because of vanishing gradient descent problems

6. User wasserstein loss, aim to minimize the distance between generated and real AI.

7. Critic vs discriminators, in critics we have different values and there are some limits on critis.

8. The first limit is that the gradients be at most 1 : wieght clipping, gradient penalty 

9. Conditional generation : classes we want + input matrix + noise

10. Controabble : features we want + input matrix + noise

11. Challenges: Entanglement and correlation between features.

12. To solve the challenges 1)classifier gradient: to use a classifier module and 2)disentaglement.

----

## Course 2

1. Evaluate GANs because discriminators are overfitting to your generative models and we don't have a universal discriminator.

2. Fidelity : quality or realism of image vs Diversity : variety of images

3. Comparing image : Pixel distance (isnt reliable), Feature distance (less sensetive to shifts)

4. FID : A lower FID score indicates that the generated images are closer to the real images

5. Inception score

6. Sampling and Truncation

7. Precision and Recall

8. Disadvantages : lack of intrinsic evaluation metric

9. Alternatives: VAE, Autoregressive Models, Flow Models

10. Bias and Fairness in Model

11. Adversial loss for solving bias

12. StyleGAN : progressive growing (avoid mode collapse and create high resolution images), noise mapping network (variation and randomness), adaptive instance normalization (control the style of generated images according to desired style).

---

## Course 3

1. Gan usage in Data augmentation, image to image translation, medicine and climate change, text to image, adverserial area.

2. Paried image to image translation using Pix2Pix which transfer style of one image to another image.

3. PatchGAN and U-Net architecture and pixel distance loss term.

4. CycleGAN and Cycle consistency

5. Least square and identity loss (input and output are same) which helps to preserve the color.
