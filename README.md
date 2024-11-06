**Enhancing Autism Diagnosis via Video-Based Analysis of Neurodevelopmental Child Behavior** : 
Autism Spectrum Disorder (ASD) represents a heterogeneous set of neurobiological disorders characterized by defects in social communication and reciprocal interactions, repetitive, as well as stereotypic behaviors.
When the children are performing their regular day-today activities, some of the self-stimulatory behaviors, such as arm flapping, head banging, or spinning behaviors can be studied by automatically analysing the captured videos.
![image](https://github.com/user-attachments/assets/d77857e2-87ca-42ae-b12e-1d03a7d21654)


**Problem Statement** : 
Develop an automated system for detecting and analyzing self-stimulatory behaviors in children with Autism Spectrum Disorder (ASD) through the analysis of video footage. The system understands the patterns of behaviors such as arm flapping, head banging, and spinning and provides the doctors with a detailed behavior analysis of patients.
Utilize pose estimation algorithms and motion analysis techniques to extract relevant features from the video frames. Train machine learning models, such as Convolutional Neural Networks (CNNs) and Recurrent Neural Networks (RNNs), to detect and classify self-stimulatory behaviors.
The standard action recognition pipeline of interest point detection, feature extraction, generation of feature descriptors, model training and using it for recognition for a test video is to be followed on the dataset. 
The well-known Space Time Interest Points (STIP) employed with Harris3D detectors in a Bag Of Words (BOW) framework is to be used to train a 3-class classifier. The three classes are arm flapping, head banging and spinning corresponding to the videos in the dataset.

