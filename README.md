# Genre-Effect-Towards-Developing-a-Multi-modal-Movie-Recommendation-System-in-Indian-Setting
A classification-based Recommendation System on the Hindi Movie dataset, Flickslore.


In contemporary times, the Recommendation System (RS), a subset of information filtering systems, requires no formal introduction. The movie recommendation system holds a pivotal role in streaming platforms, where an extensive library
of movies necessitates meticulous analysis to curate a tailored selection for users. Predominantly, existing datasets comprise user-movie pair ratings, consequently motivating research on regression-based approaches to predict user-movie 
rating values. Remarkably, our investigation reveals a notable gap in the literature concerning datasets specifically oriented towards Indian regional languages, incorporating user feedback in ordinal values. This underscores the need for 
exploration in this domain, addressing an unmet research area. This paper presents an innovative recommendation system designed for a multi-modal Hindi movie dataset that incorporates user feedback categorized into three distinct 
classes: ”Dis-like,” ”Like,” and ”Neutral/Not watched”. The system leverages multi-head cross-attention mechanisms and utilizes audio-video data sourced from Hindi movie trailers within the Flickscore dataset. Furthermore, we conduct an 
extensive examination of a classification-based model, evaluating its effectiveness in two crucial aspects: (i) GenreLike-Score (GL-score), a novel metric we devised to align user genre preferences with movie genres, and (ii) various 
Audio/Video embeddings. The paper explores the performance of different combinations of these factors across different dataset modalities and establishes that GL-score significantly contributes to preference prediction. Additionally, 
the study delves into the assessment of diverse keyframe extraction techniques and introduces distinct modality-specific embedding processes. These findings collectively enhance our understanding of recommendation systems and their 
application to multi-modal datasets.

![Main_model](https://github.com/prrabirmondal/Genre-Effect-Towards-Developing-a-Multi-modal-Movie-Recommendation-System-in-Indian-Setting/assets/93509969/b3664e6a-f112-4b52-a448-e9e06dd2477c)

------------------------------------------------------------------------------------------------
# The file details in the repo:


    1) Single_frame_SceneDetection.ipynb :   This file contains code for extracting the single keyframe from the movie trailer using the PySceneDetect python module.
 
    2) PySceneDetect_YOLO.ipynb: This Jupyter notebook contains code for extracting frames from movie trailers using PySceneDetect for scene Detection and the YOLO model for further object detection.

    3) Resnet_model.ipynb: This Jupyter notebook contains code for generating video embedding using a pre-trained Resnet50 model.

    4) TimesFormer_for_VideoEmbedding.ipynb: This code file generates video embedding  using the TimesFormer model.

    5) Genre_based_audio_embedding.ipynb: This code file is used for generating genre-based video embedding. 

    6) Preference_based_UserEmbedding.ipynb: This Jupyter notebook contains code for calculating GL score and creating user embedding. 

    7) Simple_neural_network.ipynb: This notebook contains code for generating results using a simple neural network. 

    8) Single_Modality_Classification.ipynb:This notebook contains code of final model for generating results using cross attention model for single modality .
 
    9) All_Modality_Classification.ipynb:This notebook contains code of final model for generating results using cross attention model for Bi-modality . 
