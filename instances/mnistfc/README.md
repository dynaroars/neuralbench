network:	 mnist-net_256x2.onnx
input_dim: 	 [784]
model:
ConvertModel(
  (Flatten_7): Flatten()
  (Gemm_8): Linear(in_features=784, out_features=256, bias=True)
  (Relu_9): ReLU(inplace=True)
  (Gemm_10): Linear(in_features=256, out_features=256, bias=True)
  (Relu_11): ReLU(inplace=True)
  (Gemm_12): Linear(in_features=256, out_features=10, bias=True)
)
network:	 mnist-net_256x4.onnx
input_dim: 	 [784]
model:
ConvertModel(
  (Flatten_11): Flatten()
  (Gemm_12): Linear(in_features=784, out_features=256, bias=True)
  (Relu_13): ReLU(inplace=True)
  (Gemm_14): Linear(in_features=256, out_features=256, bias=True)
  (Relu_15): ReLU(inplace=True)
  (Gemm_16): Linear(in_features=256, out_features=256, bias=True)
  (Relu_17): ReLU(inplace=True)
  (Gemm_18): Linear(in_features=256, out_features=256, bias=True)
  (Relu_19): ReLU(inplace=True)
  (Gemm_20): Linear(in_features=256, out_features=10, bias=True)
)
network:	 mnist-net_256x6.onnx
input_dim: 	 [784]
model:
ConvertModel(
  (Flatten_15): Flatten()
  (Gemm_16): Linear(in_features=784, out_features=256, bias=True)
  (Relu_17): ReLU(inplace=True)
  (Gemm_18): Linear(in_features=256, out_features=256, bias=True)
  (Relu_19): ReLU(inplace=True)
  (Gemm_20): Linear(in_features=256, out_features=256, bias=True)
  (Relu_21): ReLU(inplace=True)
  (Gemm_22): Linear(in_features=256, out_features=256, bias=True)
  (Relu_23): ReLU(inplace=True)
  (Gemm_24): Linear(in_features=256, out_features=256, bias=True)
  (Relu_25): ReLU(inplace=True)
  (Gemm_26): Linear(in_features=256, out_features=256, bias=True)
  (Relu_27): ReLU(inplace=True)
  (Gemm_28): Linear(in_features=256, out_features=10, bias=True)
)
