# Multimodal-Image-Retrieval

The following code has been trained on Flickr30K dataset. <br>

Step 1: The baseline model is openAI's CLIP model. It basically projects dataset into the same latent space. The notebook consists of training as well as inferences. <br><br>
Step 2: The second model we formulate is Image Captioning(Show-and-Tell) + Text Vecorizer. The script for that is found in show-and-tell.ipyn. The script generates captions over test set which can be found in show_tell_caption.csv <br><br>
We later on use these captions for inferences in Inference_Image_Caption+Similaity. <br>
Step 3: The third model we formulate is Image Captioning(Show-Attend-and-Tell) + Text Vecorizer. The script for that is found in ImageCaptioning-Show-Attend-And-Tell..ipyn. The script generates captions over test set which can be found in valid_df_attention.csv
We later on use these captions for inferences in Inference_Image_Caption+Similaity <br><br>
