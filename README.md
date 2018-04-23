# Useful Docker Files
This repository contains docker files that I created/modified and find useful. Here is a quick description of dockerfiles:

* **tensorflow-serving.devel**: This dockerfile is a modified version of dockerfile available at [official tensorflow-serving repo](https://github.com/tensorflow/serving/blob/5369880e9143aa00d586ee536c12b04e945a977c/tensorflow_serving/tools/docker/Dockerfile.devel). 
But unlike official dockerfile, this dockerfile doesn't require you to run any commands or build the code. 
This dockerfile is a ready-to-launch tensor_flow server and contains everything you need! 
Just build this dockerfile and launch it with required binding with port 9000, and your model directory mounted at `/model`.
