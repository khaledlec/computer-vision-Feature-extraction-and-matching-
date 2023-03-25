# Computer Vision Feature Extraction and Matching Techniques:

__Computer vision__ is a field of study that focuses on enabling machines to interpret, analyze, and understand visual data from the world around us. It involves processing and analyzing images or videos to extract useful information, such as object recognition, motion estimation, and scene understanding.


Computer vision can be broadly categorized into three main areas: low-level vision, mid-level vision, and high-level vision. However, the distinction between these levels is not always clear-cut and can vary depending on the task at hand.

Low-level vision focuses on processing the raw pixel data of an image, such as brightness, color, and texture. Techniques used in low-level vision include image preprocessing, filtering, edge detection, corner detection, and feature extraction. These techniques are used to enhance image quality, detect edges and corners, and extract basic features that can be used in higher-level vision tasks.

Mid-level vision focuses on understanding the context and structure of an image, such as object segmentation, object recognition, and motion estimation. Mid-level vision techniques include clustering, segmentation, object detection, optical flow analysis, feature extraction, and matching. These techniques are used to group pixels into meaningful objects, identify objects in an image, track their motion over time, and match features between images.

It's worth noting that some mid-level vision techniques, such as feature extraction and matching, can be considered as first-level vision techniques because they involve processing raw pixel data to extract meaningful features that can be used for higher-level tasks.

High-level vision focuses on understanding the semantics of an image, such as object classification, scene understanding, and activity recognition. High-level vision techniques include machine learning, deep learning, and artificial intelligence algorithms. These techniques are used to analyze the content of an image and infer its meaning, such as recognizing objects, scenes, and activities.

We will focuse on the mid-level: Image matching, feature extraction and alignment.

There are 5 main techniques we will practice here:

__Hu Moments__: Hu Moments are a set of image descriptors that are used for shape recognition and analysis. These moments capture the shape of an object by computing its moments of inertia. They are invariant to translation, rotation, and scaling, making them useful for feature extraction and matching.

In this notebook __Invariant moments and similarity metric.ipynb__ we pick the __pegasus-unicorn__ image we perform difrent preprocessing steps using open cv to generate images of the same unicorn but difrent variations(translation, rotation, and scaling..) and prove that with the use of the right similarity metric and normalization this methode can help in object detection.

__Block Comparing Technique__: The Block Comparing Technique is used to compare two images by dividing them into blocks and computing the differences between corresponding blocks. This technique is often used for image registration and alignment.

__Scale-Invariant Feature Transform (SIFT)__: SIFT is a feature extraction technique that detects and extracts distinctive and invariant features from an image. These features can be used for image matching, object recognition, and scene reconstruction. SIFT is robust to changes in scale, rotation, and illumination, making it a popular choice for many computer vision applications.

__Speeded Up Robust Feature (SURF)__: SURF is a feature extraction technique that is similar to SIFT but is designed to be faster and more efficient. It uses a similar approach to detect and extract features, but it relies on a simpler algorithm for computation.

__Dynamic Time Warping (DTW)__: DTW is a technique used for measuring similarity between two time series by warping them to align with each other. It is often used in speech recognition, gesture recognition, and pattern recognition.

Each of these techniques plays a crucial role in mid-level computer vision tasks such as image matching, feature extraction, and alignment. By combining these techniques with other computer vision algorithms and tools, it is possible to develop powerful and effective computer vision systems for a wide range of applications.

