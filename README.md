Crack segmentation tools

1. (recommended for 1-2 pictures) Simplest one, slow, drag-and-drop graphical interface:
   https://huggingface.co/spaces/toth235a/crack_demo
   Just drag the image file to the middle of the left box, over "Drop Image Here" text (the border of the box becomes red if you do it right), click submit, and you have the segmentation results in 40 seconds (for a 512 by 512 image).
   
2. (recommended for 3-20 pictures) Kaggle notebook, still very simple and much faster, but you need to create a kaggle account (takes 2 seconds with your google account, preferebly your private one). Kaggle lets you use a GPU for 30 hours/week which makes the algorithm run much faster:
   https://www.kaggle.com/code/displayedfullname2/notebook6c440f9989
   Log in/sign up and click on the Copy and edit button to start the notebook.
  
3. If you do not want to create a kaggle account, you can use Google colab, you just need a google account (you may have to use your private account as the company account may not work). In Google colab, you get less free GPU resources:
   [https://github.com/toth235a/cracks/blob/main/Crack_segmentation_with_Mask2Former.ipynb](https://colab.research.google.com/github/toth235a/cracks/blob/main/Crack_segmentation_with_Mask2Former.ipynb)
