Description
============
Opens live video feed, segments objects from each frame, feeds into tensorflow neural network classifier, trained with the tensorflow object detection API, and tracks object across multiple frames


Run this command in the root directory of project:
protoc object_detection/protos/*.proto --python_out=.
this compiles all the proto files in object_detection/protos into python