# Autoencoders_Applications
here i develop different projects on use cases for auto encoders!
- DenoisingAutoencoders.ipynb:
    - Here I had the opportunity of working with a really large dataset (taken from [here](https://www.kaggle.com/datasets/greatgamedota/ffhq-face-data-set/data]))
    - I tried using the GPU on colab but i had different issues with loading from the Drive all the files in a fast way
    - I decided to use this project as a learning experience but to start with a smaller subset
    - Observations:
        - The heterogeinity of the images was more captured when i used a smaller batch size!
        - The weight decay was not useful!
        -  With a really small loss, is really important to decrease fastly the learning rate!
        -  There were not many projects available that used this architecture to denoise RGB images!
