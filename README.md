# Task overview
You are provided with a single high-resolution image that contains multiple sheep. Your task is to explore how
self-supervised visual representations can be used to analyze and count the objects in the scene. The solution
does not need to be general. You can make assumptions specific to this image.
## 1. Feature extraction
Use a Vision Transformer variant of the DINO v3 model (a configuration that can be run comfortably on the
machine available to you) to extract a spatial feature map of the image.
## 2. PCA visualization
Perform a Principal Component Analysis (PCA) on the extracted feature map to visualize and interpret the
feature representation.
## 3. Counting with a known location
You are informed that there is a sheep located at coordinates (x=1300, y=650) in the image. Using this
knowledge as a starting point, propose and implement an algorithm that estimates the total number of sheep in
the image.
## 4. Counting without prior knowledge
Design an alternative approach that estimates the number of sheep without relying on any known locations.
