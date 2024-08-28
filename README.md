# Panoramic-Image-Stiching-cv2
Pipeline to Stich overlapping images to create a panoramic. ENPM673 Project II Part 2

## Description
Image processing pipeline to stitch four images to create a panoramic image.

## Dependencies
To run the code, make sure the following python libraries are installed
1. cv2
2. numpy
3. matplotlib

## Installation of Dependencies 

```bash
sudo apt update
sudo apt-get install python3-opencv python3-numpy python3-matplotlib
  
```


## Pipeline
1. Extract features from each frame
2. Match the features between each consecutive image.
3. Compute the homographies between the pairs of images.
4. Combine these frames together using the computed homographies.


## Images 

Feature Matching Between Image 1 and Image 2

![output](https://github.com/user-attachments/assets/a2b7764d-ce6c-4074-ba28-97c181dcb828)

Feature Matching Between Image 2 and Image 3

![output2](https://github.com/user-attachments/assets/1a213d8d-c66f-430e-bf4d-abd0036bcae7)


Feature Matching Between Image 3 and Image 4

![output3](https://github.com/user-attachments/assets/e59c52cb-bb06-42e4-9a05-82b61b77e087)



Stiching Image 1 and 2 

![output4](https://github.com/user-attachments/assets/9be22790-314f-403c-8b47-2e2bbfa74e8b)


Stiching Image 3 to the stiched image
![output5](https://github.com/user-attachments/assets/8c4ec183-070a-464e-b288-b2d32ecee1a8)

Stiching Image 4 to the stiched Image

![output5](https://github.com/user-attachments/assets/78e67569-0486-4739-aa93-b1b26b0f9247)

Resulting Panoromic Image 
![output6](https://github.com/user-attachments/assets/788836db-ec31-4c49-bec3-a50bf13f9a13)
