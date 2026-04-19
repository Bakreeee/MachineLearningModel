# Face Recognition in Group Photos

This project is a Jupyter Notebook-based tool that allows you to find a specific person within a group photograph. It uses OpenCV for face detection and the `imgbeddings` library to compute and compare facial embeddings.

## Features
- Prompts the user to input paths for a target person's image and a group image.
- Detects faces in both images using OpenCV's Haar Cascades.
- Extracts deep image embeddings for the detected faces using `imgbeddings`.
- Compares the embeddings using Euclidean distance to find the closest match.
- Highlights the matched person in the group photo with a red bounding box and displays the result directly in the notebook.
