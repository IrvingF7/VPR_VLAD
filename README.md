# Introduction
This is a simple class project that uses [VLAD feature](https://ieeexplore.ieee.org/document/6619051) to build a large scale VPR (Visual Place Recognition) system. More details can be found in the markdown section of the notebook.

# Requirement and Run
Besides some of the common default Python package,you will need `numpy`, `scikit-learn` and `OpenCV >= 4.4` as the code uses SIFT feature detector that's only available after that specific version.

To run the code on any database of images and with customized query, replace the `database_path` and `query_path` to different folders and run the entire notebook. It may takes a while to index all the images in the database.
