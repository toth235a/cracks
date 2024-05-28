Crack segmentation tools

1. (just for trying out) Simplest one, slow, drag-and-drop graphical interface:
   https://huggingface.co/spaces/toth235a/crack_demo
   Just drag the image file with a concrete crack in it to the middle of the left box, over "Drop Image Here" text (the border of the box becomes red if you do it right), click submit, and you have the segmentation results in 40 seconds (for a 512 by 512 image).

2. (if you have a computer with a GPU) https://github.com/toth235a/ViT-Adapter/blob/main/segmentation/README.md
   
3. (colab - prediction of concrete cracks if you do not have a GPU) You just need a google account (you may have to use your private google account as the company account may not work). May work with the free version of colab. https://colab.research.google.com/github/toth235a/cracks/blob/main/Prediction_with_a_crack_segmentation_model.ipynb
   
4. (colab - training of a new model on new data) You can retrain the model on your data if your cracks are different (masonry, asphalt, speckled surface etc.). You need colab+ (paying)
  
5. (kaggle - prediction of concrete cracks if you do not have a GPU) Kaggle is similar to colab, very easy to create an account, you probably need to verify it with your mobile phone. Gives more free resources than google.
