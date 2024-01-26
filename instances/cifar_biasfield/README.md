network:	 cifar_base.onnx
input_dim: 	 [3, 32, 32]
model:
ConvertModel(
  (Conv_onnx::Relu_17): Conv2d(3, 16, kernel_size=(3, 3), stride=(1, 1), padding=(1, 1))
  (Relu_onnx::Conv_18): ReLU(inplace=True)
  (Conv_onnx::Relu_19): Conv2d(16, 32, kernel_size=(3, 3), stride=(2, 2), padding=(1, 1))
  (Relu_onnx::Conv_20): ReLU(inplace=True)
  (Conv_onnx::Relu_21): Conv2d(32, 32, kernel_size=(3, 3), stride=(1, 1), padding=(1, 1))
  (Relu_onnx::Conv_22): ReLU(inplace=True)
  (Conv_onnx::Relu_23): Conv2d(32, 64, kernel_size=(3, 3), stride=(2, 2), padding=(1, 1))
  (Relu_onnx::Conv_24): ReLU(inplace=True)
  (Conv_onnx::Relu_25): Conv2d(64, 64, kernel_size=(3, 3), stride=(1, 1), padding=(1, 1))
  (Relu_onnx::Conv_26): ReLU(inplace=True)
  (Conv_onnx::Relu_27): Conv2d(64, 128, kernel_size=(3, 3), stride=(2, 2), padding=(1, 1))
  (Relu_onnx::Conv_28): ReLU(inplace=True)
  (Conv_onnx::Relu_29): Conv2d(128, 128, kernel_size=(3, 3), stride=(1, 1), padding=(1, 1))
  (Relu_onnx::Conv_30): ReLU(inplace=True)
  (Conv_onnx::Flatten_31): Conv2d(128, 10, kernel_size=(4, 4), stride=(1, 1))
  (Flatten_32): Flatten()
)
