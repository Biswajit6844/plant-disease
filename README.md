# plant-disease
A CNN model to classify different plant diseases. Vgg16 net is fine tuned to the crowdAI dataset. 

The dataset can be found at https://www.crowdai.org/challenges/1

# Methodology

The pre-trained VGG16 model trained on imagenet dataset was used and the last 4 convolutional layers were trained on our dataset. This process is called fine tuning.

A point to note is that only 19 classes were used from the dataset since we were focussing on a particular region where only these crops are grown.

![image](https://github.com/user-attachments/assets/10972023-484c-4523-bc60-b23e0e725f54)

![image](https://github.com/user-attachments/assets/72abfd55-290d-426b-82ee-a68770a38c27)


![image](https://github.com/user-attachments/assets/671648cb-6777-4fbc-a760-a9242a430e22)

![image](https://github.com/user-attachments/assets/32defa39-63cb-4948-8a01-a4f5822b0559)

![image](https://github.com/user-attachments/assets/c1734b1d-477c-464a-8c95-503a9b0306b5)
