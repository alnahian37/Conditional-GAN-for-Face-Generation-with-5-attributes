# https---github.com-alnahian37-Conditional-GAN-for-Face-Generation-with-5-attributes
In this repository the goal is to implement a conditional Generative Adversial Network (cGAN) that can generate human faces with certain conditions applied to the appearance of the generated images. I have used a modified version of the CelebA dataset which contains 202,559 images with 40 attributes. In my case, the dataset image size was cropped to 64x64x3 sizes and 5 out of 40 attributes were considered for conditional information.
The attributes selected was Black hair, Male-female, Oval Shaped Face, Smiling, Young. So, an input attribute of 10011 should generate a face which has black hair, is a female, not oval shaped face, smiling and young. In the generated images, one or more of the attributes are present based on the user input during the generation process.

Demo Generated images: https://drive.google.com/file/d/1Zk_W5-cLQPY-BG6GyWhr6Ck_-Nv6C82R/view?usp=drive_link
