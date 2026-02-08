# model-to-ONNX

python pytorch_ONNX.py --module QuantizedMNISTNet.py --class SmallMNISTNet --checkpoint mnist_model.pth --input-shape 1,1,28,28 --output model.onnx
