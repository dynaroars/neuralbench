
Benchmarks:

| Benchmark             | Network Type          | # Parameters  | Input Dimension | Sparsity  |
|-----------------------|-----------------------|---------------|-----------------|-----------|
| Acas XU               | FC + ReLU             | 13k           | 5               | 0-20%     |
| Carvana UNet          | Complex U-Net         | 150k - 330k   | 5828            |           |
| Cifar Biasfield       | Conv + ReLU           | 363k          | 16              |           |
| Cifar100_tinyimagenet | Conv + ReLU           |               | 3*32*32 3*56*56 |           |
| Cifar2020             | Conv + ReLU           |               | 3*32*32         |           |
| Collins_rul_cnn       | Conv + ReLU           | 60k - 262k    | 400 - 800       |           |
| dist_shift            | FC + ReLU, Sigmoid    | 342k - 855k   | 792             | 98.9%     |
| mnist_fc              | FC + ReLU             | 270k - 530k   | 784             |           |
| oval21                | Conv + ReLU           | 54k - 214k    | 3072            |           |
| reach_prob_density    | FC + ReLU             | 1.2k - 9k     | 3 - 14          |           |
| rl_benchmarks         | FC + ReLU             | 4.6k - 70k    | 4 - 8           |           |
| SRI_ResNet_A          | ResNet(Conv + ReLU)   | 345k          | 11 k            |           |
| SRI_ResNet_B          | ResNet(Conv + ReLU)   | 345k          | 11 k            |           |




- [x] Acas XU
- [ ] Carvana UNet
- [x] Cifar Biasfield
- [x] Cifar100_tinyimagenet
- [x] Cifar2020
- [x] Collins_rul_cnn
- [x] dist_shift (2 network unused)
- [x] mnist_fc
- [x] oval21
- [ ] reach_prob_density
- [ ] rl_benchmarks
- [ ] SRI_ResNet_A
- [ ] SRI_ResNet_B
