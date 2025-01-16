# Visualize-Activation-Maps
  This project demonstrates the use of Grad-CAM (Gradient-weighted Class Activation Mapping) to visualize activation maps in a Convolutional Neural Network (CNN) for emotion detection. By examining these heatmaps, we gain insights into how the model processes facial features to predict emotions, identifying which regions of an image contribute the most to its decisions.
 
  1.Train the model:
          Load the FER 2013 dataset and preprocess it using ImageDataGenerator.
          Train the CNN model using the provided script.

  2.Generate Grad-CAM visualizations:
          Specify the path to a sample image.
          Use the get_grad_cam function to generate a heatmap.
          Visualize and save the results.

  3.Evaluate the model:
          Use confusion matrix and classification report to assess model performance.
