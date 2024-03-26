# Autoencoders_Applications
Here i develop different projects on use cases for auto encoders!
- DenoisingAutoencoders.ipynb:
    - Here I had the opportunity of working with a really large dataset (taken from [here](https://www.kaggle.com/datasets/greatgamedota/ffhq-face-data-set/data]))
    - I tried using the GPU on colab but i had different issues with loading from the Drive all the files in a fast way
    - I decided to use this Dataset as a learning experience but to start with a smaller subset around 24k
    - **Observations**:
        - The heterogeinity of the images was more captured when I used a smaller batch size!
        - The weight decay was not useful!
        - With a really small loss, is really important to decrease fastly the learning rate!
        - For comparison, there were not many projects available that used this architecture to denoise RGB images!
     
- Autoencoder_AnomalyDetection.ipynb:
  
      - Several problems here:
          - poor performances!
          - I used a validation set for choosing the best threshold
          - I used the split of the validation set with only healthy cell to check the loss during the training!
