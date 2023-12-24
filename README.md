# Resume Classification

This project focuses on classifying resume images using a convolutional neural network (CNN). The dataset consists of 77 resume images and 76 non-resume images, including 60 from the CIFAR-10 dataset and 16 additional images.

### Steps to Use the Code:
   - Open the `CV_Assgnment.ipynb` Notebook.
   - Run the first two code snippets to load the imports and create directories.
   - Add resume_data images to the 'resume' folder and nonresume_data images to the 'ext' folder.
   - Run the code cells sequentially to preprocess data, build, train, and test the CNN model.

 **Testing with Custom Image:**
   - Change the file path in the last code snippet to test any image for prediction.

### File Structure:
dataset/
resume/
resume_image_1.jpg
resume_image_2.jpg
...
ext/
ext_image_1.jpg
ext_image_2.jpg

### Additional Notes:

- Credit to CIFAR-10 for provided dataset images.
- Model predictions for custom images can be obtained by modifying the file path in the code.
