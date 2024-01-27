network:	 mnist_concat.onnx
input_dim: 	 [792]
model:
ConvertModel(
  (Gemm_input.1): Linear(in_features=792, out_features=200, bias=True)
  (Relu_onnx::Gemm_10): ReLU(inplace=True)
  (Gemm_x_z): Linear(in_features=200, out_features=784, bias=True)
  (Sigmoid_onnx::Reshape_12): Sigmoid()
  (Reshape_output): Reshape(shape=[-1  1 28 28])
  (Reshape_cls/onnx::Gemm_8): Flatten()
  (Gemm_cls/onnx::Relu_9): Linear(in_features=784, out_features=32, bias=True)
  (Relu_cls/onnx::Gemm_10): ReLU(inplace=True)
  (Gemm_cls/onnx::Relu_11): Linear(in_features=32, out_features=32, bias=True)
  (Relu_cls/onnx::Gemm_12): ReLU(inplace=True)
  (Gemm_cls/output): Linear(in_features=32, out_features=10, bias=True)
)
