# VisTales



The Visual Storytelling (VIST) dataset tackles the challenge of matching image sequences with meaningful natural language stories. In this project, we developed a system that creates short narratives based on sets of three images from the VIST dataset. 

Our method uses CLIP to extract visual features and a pretrained GPT-2 language model to generate the text.



This system is built to handle carefully selected image-caption pairs, combining visual and language inputs to produce context-aware stories. During training, we guide the language model using the visual information from CLIP, and train it using standard language modeling techniques. We assess the system's performance using training loss and sample outputs, showing that it can create stories that are both logically structured and grammatically sound.



NOTE:

The sis.json file is not included, which is the training json file for VIST Story-in-sequence file. The training images used were not attached due to its large size (13k images and around 23 GB). However, can be downloaded from VIST under then name train\_split0.tar.gz. Both files are also uploaded as Kaggle datasets for you to view if needed (ishaan\_iyer\_ii10/sis\_646 and ishaan\_iyer\_ii10/vist\_646).

