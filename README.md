# Post-Hashtag-Incongruity
Hybrid Multi-Modal Deep Learning for Detecting Hashtag Incongruity

### Abstract

Hashtags have been an integral element of social media platforms over the years and are widely used by users to promote, organize, and connect users. Despite the intensive use of hashtags, there is no basis for using congruous tags, which causes the creation of many unrelated contents in hashtag searches. The presence of mismatched content in the hashtag creates many problems for individuals and brands. Although several methods have been presented to solve the problem by recommending hashtags based on the users’ interest, the detection and analyzing the characteristics of these repetitive contents with irrelevant hashtags have rarely been addressed. To this end, we propose a novel hybrid deep learning hashtag incongruity detection by fusing visual and textual modality. We fine-tune BERT and ResNet50 pre-trained models to encode textual and visual information to encode textual and visual data simultaneously. We further attempt to show the capability of logo detection and face recognition in discriminating images. To extract faces, we introduce a pipeline that ranks faces based on the number of their appearance on Instagram accounts using face clustering. Moreover, we conduct our analysis and experiments on a dataset of Instagram posts that we collect from hashtags related to brands and celebrities. Unlike the existing works, we analyze these contents from both content and user perspectives and show a significant difference between data. In light of our results, we show that our multimodal model outperforms other models and the effectiveness of object detection to detect mismatched information.

-------------

<img width="568" alt="multimodal_git" src="https://user-images.githubusercontent.com/47991444/198833802-cf755327-f906-46b6-80e5-893779305bb2.png">
<img width="568" alt="face recognition_git" src="https://user-images.githubusercontent.com/47991444/198833465-dc916186-628a-402b-90d8-133ce35d509f.png">

-------------

| Dataset  | Description | Google Drive Link |
| ------------- | ------------- | ------------- |
| Visual data  | Instagram Images and profile picture | [Link](https://drive.google.com/drive/folders/1yqd_8G3y9wIKF3qrmK0di-U8BExaitvB?usp=share_link) |
| Metadata | User engagement and post networks information | [Link](https://drive.google.com/drive/folders/1WGf5QrmrPnAcqtAUgWM9PKm1v8kvp9FN?usp=share_link) |
| Textual data  | Instagram captions and texts extracted from images | [Link](https://drive.google.com/drive/folders/1f_Updim7Ug4vn6W-69v3iV8RSriTV2n3?usp=share_link) |
| Object detection data | Faces and Logos data for training the object detection models | [Link](https://drive.google.com/drive/folders/174aNN58CqlWum6SY1AzJr4e1u2o_X3bT?usp=share_link) |

-------------

### Experimental Settings
* Python: 3.7.15
* TensorFlow: 2.9.2
* Keras: 2.9.0
* GPU: NVIDIA Tesla T4
