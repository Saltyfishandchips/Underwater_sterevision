# Underwater_sterevision
  We borrowed this link: https://github.com/The-Learning-And-Vision-Atelier-LAVA/PAM, and used the PAM network to perform stereo matching on the underwater binocular image. Due to the characteristics of the underwater image itself, We first used the Retinex algorithm to enhance the underwater binocular image, enhanced the feature texture of the close-range target, and then fed it into the model.  
  The effect is as follows：  
![left](https://user-images.githubusercontent.com/75468763/156276380-43d63817-4207-4276-8f9b-58895c1a6191.jpg)  
![right](https://user-images.githubusercontent.com/75468763/156277077-496393d2-962c-4bd5-91ff-a7a8a3b25643.jpg)  
![disp](https://user-images.githubusercontent.com/75468763/156277332-64257f50-e085-4670-93fd-977f53a98cba.png)  
  However, due to the use of Retinex enhancement, many noises are generated in the part of the dataset without close-range targets, which seriously interferes with the training of the model.
