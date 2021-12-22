Description:

Gesture recognition becomes popular in recent years since it can play an essential role in non-verbal communication, emotion analysis as well as human-computer interaction. The research task is to detect hand gestures in raw news videos which are streams of RGB images. I propose a Transformer and keypoints-based pose tracking system and a Transformer and keypoints-based gesture detector to fulfill this task. This structure is composed of a keypoints extractor, a person tracker, and a gesture detector. The mission has three main parts, the first part is to track people in temporal space. In the second part, for each person, we use their hand keypoints features in temporal space to construct several keypoints sequences. The third part is to use these sequences to make predictions of the existence of gestures. I believe that for gesture detection tasks, both spatial and temporal information is important. So that is why we use the Transformer which can take into account the local information of hand keypoints in one frame to capture the shape information and it values also the relationship of keypoints in different frames that is the global information refer to the motion.

The dataset for our project is available at https://chalearnlap.cvc.uab.cat/dataset/22/description/. I have worked with ICPR 16 dataset to train the gesture detection model.

![image](https://user-images.githubusercontent.com/57759564/147103718-e135d9c0-2569-4275-874f-24c7d3e4b971.png)


![image](https://user-images.githubusercontent.com/57759564/147103788-d2728c34-634c-42ec-9258-26a5e6a78fbf.png)
