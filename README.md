# Visualize-Activation-Maps
  This project demonstrates the use of Grad-CAM (Gradient-weighted Class Activation Mapping) to visualize activation maps in a Convolutional Neural Network (CNN) for emotion detection. By examining these heatmaps, we gain insights into how the model processes facial features to predict emotions, identifying which regions of an image contribute the most to its decisions.

NOTE :
      Dataset Setup:
                    To train and test the model, download the FER-2013 dataset from Kaggle: FER-2013 Dataset.
                    Once downloaded, place the dataset in the project directory under the folder data/fer2013.

Installation:
  Clone the repository:
                    git clone https://github.com/yourusername/emotion-detection-with-gradcam.git
                    cd emotion-detection-with-gradcam

  Install dependencies:
                    pip install -r requirements.txt
                    
Usage:
  1.Train the model:
          Load the FER 2013 dataset and preprocess it using ImageDataGenerator.
          Train the CNN model using the provided script.

  2.Generate Grad-CAM visualizations:
          Specify the path to a sample image.
          Use the get_grad_cam function to generate a heatmap.
          Visualize and save the results.

  3.Evaluate the model:
          Use confusion matrix and classification report to assess model performance.

🎯 Outputs:
Original Image: The input image used for prediction.
Grad-CAM Heatmap: Highlights regions of interest that influence the model's decision.
Superimposed Image: Combines the heatmap with the original image for a clearer visualization.

📖 References:
FER 2013 Dataset
Grad-CAM Paper
