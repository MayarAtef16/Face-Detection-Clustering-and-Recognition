# Face-Detection-Clustering-and-Recognition
## Introduction

>A method of recognizing or verifying a person's identification using their face is facial recognition. People can be recognized using facial recognition technology in real-time or in still images and videos. A subcategory of biometric security is facial recognition. Face recognition is done through four main steps. The first step is face detection by which the camera identifies and locates an individual or group of individuals' faces. The subject may be shown facing directly ahead or in profile. The second step is face analysis where the software identifies the geometry of your face. The distance between your eyes, the depth of your eye sockets, the space between your forehead and chin, the form of your cheekbones, and the shape of your lips, ears, and chin are all important considerations. The objective is to recognize the distinctive facial features that make your face unique. Consequently, converting image to data takes place where based on the subject's facial features, the face capture process converts analog information into a collection of digital information. The examination of your face is reduced to a mathematical formula. Finally, a database of other recognized faces is used to compare your faceprint produced in the previous step. Although there is growing interest in using the technology in other areas, security and law enforcement still account for the majority of its uses <br />
<space>The process of grouping faces based on their underlying identities is called face clustering. Although it has several key distinctions from the face recognition issue, it is closely related to that issue. Assuming that the identities of the subjects in the gallery or enrollment are known in advance, the objective of face recognition is to verify a 1:1 comparison against an enrollment face image or find a 1:N comparison against a face gallery the identity of a given subject. Face recognition might therefore be categorized as a supervised classification task. Face clustering, in contrast, is regarded as an unsupervised classification issue because no labeled data are presented
  

## Overall Protocol
  1- Upload folder of the dataset with name "" <br />
  2- Get the images with faces in Dataset folder only with detection <br />
  3- Clustering the images in Dataset folder  <br />
  4- pass any image to the recognition pipeline to know the face belongs to whom <br />
  

### 1. Setup
  Necessary packages should be installed to run the code. Dependecies:<br />
    * DeepFace<br />
    * numpy<br />
    * pandas<br />
    * matlibplot<br />
    * os<br />
### 2. Datasets
  
### 3. Installation DeepFace Package
>pip install deepface  
### 4. Detection
  1- make a new directory to save the images with detected faces<br />
  >os.mkdir("/content/DetectedFaces")<br />
  
  2- pass all images in the dataset folder with "dp" path to the detectface function to detect the faces<br />
  >dp="/content/Dataset"<br />
  
  3- save the detected faces and get the total face images<br />
  
  
  
### 5. Clustering

### 6. Recognition
  
  
