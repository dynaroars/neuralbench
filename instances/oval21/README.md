network:	 cifar_base_kw.onnx
input_dim: 	 [3, 32, 32]
model:
ConvertModel(
  (Conv_9): Conv2d(3, 8, kernel_size=(4, 4), stride=(2, 2), padding=(1, 1))
  (Relu_10): ReLU(inplace=True)
  (Conv_11): Conv2d(8, 16, kernel_size=(4, 4), stride=(2, 2), padding=(1, 1))
  (Relu_12): ReLU(inplace=True)
  (Flatten_13): Flatten()
  (Gemm_14): Linear(in_features=1024, out_features=100, bias=True)
  (Relu_15): ReLU(inplace=True)
  (Gemm_16): Linear(in_features=100, out_features=10, bias=True)
)
network:	 cifar_deep_kw.onnx
input_dim: 	 [3, 32, 32]
model:
ConvertModel(
  (Conv_13): Conv2d(3, 8, kernel_size=(4, 4), stride=(2, 2), padding=(1, 1))
  (Relu_14): ReLU(inplace=True)
  (Conv_15): Conv2d(8, 8, kernel_size=(3, 3), stride=(1, 1), padding=(1, 1))
  (Relu_16): ReLU(inplace=True)
  (Conv_17): Conv2d(8, 8, kernel_size=(3, 3), stride=(1, 1), padding=(1, 1))
  (Relu_18): ReLU(inplace=True)
  (Conv_19): Conv2d(8, 8, kernel_size=(4, 4), stride=(2, 2), padding=(1, 1))
  (Relu_20): ReLU(inplace=True)
  (Flatten_21): Flatten()
  (Gemm_22): Linear(in_features=512, out_features=100, bias=True)
  (Relu_23): ReLU(inplace=True)
  (Gemm_24): Linear(in_features=100, out_features=10, bias=True)
)
network:	 cifar_wide_kw.onnx
input_dim: 	 [3, 32, 32]
model:
ConvertModel(
  (Conv_9): Conv2d(3, 16, kernel_size=(4, 4), stride=(2, 2), padding=(1, 1))
  (Relu_10): ReLU(inplace=True)
  (Conv_11): Conv2d(16, 32, kernel_size=(4, 4), stride=(2, 2), padding=(1, 1))
  (Relu_12): ReLU(inplace=True)
  (Flatten_13): Flatten()
  (Gemm_14): Linear(in_features=2048, out_features=100, bias=True)
  (Relu_15): ReLU(inplace=True)
  (Gemm_16): Linear(in_features=100, out_features=10, bias=True)
)
