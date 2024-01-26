network:	 NN_rul_small_window_20.onnx
input_dim: 	 [0, 20, 20]
model:
ConvertModel(
  (Conv_conv_1): Conv2d(1, 5, kernel_size=(5, 1), stride=(1, 1))
  (Relu_relu_1): ReLU(inplace=True)
  (Conv_conv_2): Conv2d(5, 10, kernel_size=(5, 1), stride=(1, 1))
  (Relu_relu_2): ReLU(inplace=True)
  (Conv_conv_3): Conv2d(10, 5, kernel_size=(5, 1), stride=(1, 1))
  (Relu_relu_3): ReLU(inplace=True)
  (Conv_conv_4): Conv2d(5, 5, kernel_size=(3, 1), stride=(1, 1))
  (Relu_relu_4): ReLU(inplace=True)
  (Conv_fc_1): Conv2d(5, 100, kernel_size=(6, 20), stride=(1, 1))
  (Relu_relu_5): ReLU(inplace=True)
  (Dropout_dropout): Identity()
  (Conv_fc_2): Conv2d(100, 1, kernel_size=(1, 1), stride=(1, 1))
  (Flatten_fc_2_Flatten): Flatten()
)
network:	 NN_rul_full_window_20.onnx
input_dim: 	 [0, 20, 20]
model:
ConvertModel(
  (Conv_conv_1): Conv2d(1, 10, kernel_size=(5, 1), stride=(1, 1))
  (Relu_relu_1): ReLU(inplace=True)
  (Conv_conv_2): Conv2d(10, 20, kernel_size=(5, 1), stride=(1, 1))
  (Relu_relu_2): ReLU(inplace=True)
  (Conv_conv_3): Conv2d(20, 10, kernel_size=(5, 1), stride=(1, 1))
  (Relu_relu_3): ReLU(inplace=True)
  (Conv_conv_4): Conv2d(10, 5, kernel_size=(3, 1), stride=(1, 1))
  (Relu_relu_4): ReLU(inplace=True)
  (Conv_fc_1): Conv2d(5, 100, kernel_size=(6, 20), stride=(1, 1))
  (Relu_relu_5): ReLU(inplace=True)
  (Dropout_dropout): Identity()
  (Conv_fc_2): Conv2d(100, 1, kernel_size=(1, 1), stride=(1, 1))
  (Flatten_fc_2_Flatten): Flatten()
)
network:	 NN_rul_full_window_40.onnx
input_dim: 	 [0, 40, 20]
model:
ConvertModel(
  (Conv_conv_1): Conv2d(1, 10, kernel_size=(5, 1), stride=(1, 1))
  (Relu_relu_1): ReLU(inplace=True)
  (Conv_conv_2): Conv2d(10, 20, kernel_size=(5, 1), stride=(1, 1))
  (Relu_relu_2): ReLU(inplace=True)
  (Conv_conv_3): Conv2d(20, 10, kernel_size=(5, 1), stride=(1, 1))
  (Relu_relu_3): ReLU(inplace=True)
  (Conv_conv_4): Conv2d(10, 5, kernel_size=(3, 1), stride=(1, 1))
  (Relu_relu_4): ReLU(inplace=True)
  (Conv_fc_1): Conv2d(5, 100, kernel_size=(26, 20), stride=(1, 1))
  (Relu_relu_5): ReLU(inplace=True)
  (Dropout_dropout): Identity()
  (Conv_fc_2): Conv2d(100, 1, kernel_size=(1, 1), stride=(1, 1))
  (Flatten_fc_2_Flatten): Flatten()
)
