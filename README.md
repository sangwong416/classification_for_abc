# classification_for_abc
download the project and place it into the specificed model directory under jetson-inference
open command line tool
cd to jetson-inference directory
start docker by running "docker/run.sh"
cd to the project directory
run command "imagenet --model=models/abc/resnet18.onnx --labels=data/abc/labels.txt --input_blob=input_0 --output_blob=output_0 /dev/video"
