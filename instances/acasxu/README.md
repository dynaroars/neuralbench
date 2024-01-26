These is the acasxu benchmark category. The folder contains .onnx and .vnnlib files used for the category. The acasxu_instances.csv containts the full list of benchmark instances, one per line: onnx_file,vnn_lib_file,timeout_secs
 
This benchmark uses the ACAS Xu networks (from "Reluplex: An efficient SMT solver for verifying deep neural networks"), properties 1-4 run on all networks.

The .vnnlib and .csv files were created with the included generate.py script.

This benchmark is the same as in 2021/2022, and used to compare year-to-year improvements.
network:	 ACASXU_run2a_1_1_batch_2000.onnx
input_dim: 	 [5]
model:
ConvertModel(
  (Sub_input_Sub): sub()
  (Flatten_Operation_1_Flatten): Flatten()
  (MatMul_Operation_1_Add): Linear(in_features=5, out_features=50, bias=True)
  (Relu_relu_1): ReLU(inplace=True)
  (MatMul_Operation_2_Add): Linear(in_features=50, out_features=50, bias=True)
  (Relu_relu_2): ReLU(inplace=True)
  (MatMul_Operation_3_Add): Linear(in_features=50, out_features=50, bias=True)
  (Relu_relu_3): ReLU(inplace=True)
  (MatMul_Operation_4_Add): Linear(in_features=50, out_features=50, bias=True)
  (Relu_relu_4): ReLU(inplace=True)
  (MatMul_Operation_5_Add): Linear(in_features=50, out_features=50, bias=True)
  (Relu_relu_5): ReLU(inplace=True)
  (MatMul_Operation_6_Add): Linear(in_features=50, out_features=50, bias=True)
  (Relu_relu_6): ReLU(inplace=True)
  (MatMul_linear_7_Add): Linear(in_features=50, out_features=5, bias=True)
)
