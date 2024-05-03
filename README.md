Crack segmentation tools

1. Simplest one, slow, drag-and-drop graphical interface:
   https://huggingface.co/spaces/toth235a/crack_demo
   Just drag the image file to the middle of the left box, over "Drop Image Here" text, click submit, and you have the segmentation results in 40 seconds (for a 512 by 512 image).
   
2. Google colab file, still very simple, but you need a google account. In Google colab, initially you get some GPU resources and when you run out of free resources, you can buy more. When you have GPU, crack segmentation can is fast (2 seconds for a 512 by 512 image). If you only have CPU, it is slow (40 seconds per image):
   https://github.com/toth235a/cracks/blob/main/Crack_segmentation_with_Mask2Former.ipynb
