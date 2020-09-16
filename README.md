# onnx-convert-example

Simple example how to convert an PyTorch model into Tensorflow using ONNX.

Adding packages if you don't have them, if you don't need to move files to the current installation you will not need the pure-ftpd package.
```
apt install python3 python3-pip git pure-ftpd
```

Install python dependencies in order to run the convert script.
```
pip3 install torchvision
pip3 install onnx
pip3 install tensorflow
pip3 install tensorflow-addons

# To avoid "AttributeError: module 'tensorflow' has no attribute 'ceil'" --> Install onnx_tf from source, follow these steps - https://github.com/onnx/onnx-tensorflow#installation
pip3 install onnx_tf
```

Running the script 
```
python3 pytorch_to_tensorflow_lite.py models/mnist.pth models
```
