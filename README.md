# PointCloudDenoise-data

目录树如下：

```bash
.
├── examples
│   ├── PCNet_10000_poisson_0.01
│   ├── PCNet_10000_poisson_0.02
│   ├── PCNet_10000_poisson_0.03
│   ├── PCNet_50000_poisson_0.01
│   ├── PCNet_50000_poisson_0.02
│   ├── PCNet_50000_poisson_0.03
│   ├── PUNet_10000_poisson_0.01
│   ├── PUNet_10000_poisson_0.02
│   ├── PUNet_10000_poisson_0.025
│   ├── PUNet_10000_poisson_0.03
│   ├── PUNet_50000_poisson_0.01
│   ├── PUNet_50000_poisson_0.02
│   ├── PUNet_50000_poisson_0.025
│   ├── PUNet_50000_poisson_0.03
│   └── RueMadame
├── PCNet
│   ├── meshes
│   └── pointclouds
├── PUNet
│   ├── meshes
│   └── pointclouds
└── README.md
```
在examples目录下，包含了PUNet和PCNet在不同噪声水平下的点云数据，还有RueMadame数据集。针对PUNet，噪声水平分别为0.01, 0.02, 0.025和0.03；针对PCNet，噪声水平为0.01, 0.02和0.03。