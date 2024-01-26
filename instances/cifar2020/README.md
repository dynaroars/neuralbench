network:	 cifar10_2_255_simplified.onnx
input_dim: 	 [3, 32, 32]
model:
ConvertModel(
  (Conv_11): Conv2d(3, 32, kernel_size=(3, 3), stride=(1, 1), padding=(1, 1))
  (Relu_12): ReLU(inplace=True)
  (Conv_13): Conv2d(32, 32, kernel_size=(4, 4), stride=(2, 2), padding=(1, 1))
  (Relu_14): ReLU(inplace=True)
  (Conv_15): Conv2d(32, 128, kernel_size=(4, 4), stride=(2, 2), padding=(1, 1))
  (Relu_16): ReLU(inplace=True)
  (Flatten_17): Flatten()
  (Gemm_18): Linear(in_features=8192, out_features=250, bias=True)
  (Relu_19): ReLU(inplace=True)
  (Gemm_20): Linear(in_features=250, out_features=10, bias=True)
)
network:	 cifar10_8_255_simplified.onnx
input_dim: 	 [3, 32, 32]
model:
ConvertModel(
  (Conv_9): Conv2d(3, 32, kernel_size=(5, 5), stride=(2, 2), padding=(2, 2))
  (Relu_10): ReLU(inplace=True)
  (Conv_11): Conv2d(32, 128, kernel_size=(4, 4), stride=(2, 2), padding=(1, 1))
  (Relu_12): ReLU(inplace=True)
  (Flatten_13): Flatten()
  (Gemm_14): Linear(in_features=8192, out_features=250, bias=True)
  (Relu_15): ReLU(inplace=True)
  (Gemm_16): Linear(in_features=250, out_features=10, bias=True)
)
network:	 convBigRELU__PGD.onnx
input_dim: 	 [3, 32, 32]
model:
ConvertModel(
  (Constant_15): Constant(
    constant=tensor([[[[0.4914]],
    
             [[0.4822]],
    
             [[0.4465]]]])
  )
  (Sub_16): sub()
  (Constant_17): Constant(
    constant=tensor([[[[0.2023]],
    
             [[0.1994]],
    
             [[0.2010]]]])
  )
  (Div_18): Div()
  (Conv_19): Conv2d(3, 32, kernel_size=(3, 3), stride=(1, 1), padding=(1, 1))
  (Relu_20): ReLU(inplace=True)
  (Conv_21): Conv2d(32, 32, kernel_size=(4, 4), stride=(2, 2), padding=(1, 1))
  (Relu_22): ReLU(inplace=True)
  (Conv_23): Conv2d(32, 64, kernel_size=(3, 3), stride=(1, 1), padding=(1, 1))
  (Relu_24): ReLU(inplace=True)
  (Conv_25): Conv2d(64, 64, kernel_size=(4, 4), stride=(2, 2), padding=(1, 1))
  (Relu_26): ReLU(inplace=True)
  (Flatten_27): Flatten()
  (Gemm_28): Linear(in_features=4096, out_features=512, bias=True)
  (Relu_29): ReLU(inplace=True)
  (Gemm_30): Linear(in_features=512, out_features=512, bias=True)
  (Relu_31): ReLU(inplace=True)
  (Gemm_output): Linear(in_features=512, out_features=10, bias=True)
)
