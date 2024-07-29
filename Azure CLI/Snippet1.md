#Snippets

## 1 snippet

```
MaxDataDiskCount    MemoryInMB    Name                NumberOfCores    OsDiskSizeInMB    ResourceDiskSizeInMB
------------------  ------------  ------------------  ---------------  ----------------  ----------------------
2                   512           Standard_B1ls       1                1047552           4096
2                   2048          Standard_B1ms       1                1047552           4096
2                   1024          Standard_B1s        1                1047552           4096
4                   8192          Standard_B2ms       2                1047552           16384
4                   4096          Standard_B2s        2                1047552           8192
8                   16384         Standard_B4ms       4                1047552           32768
16                  32768         Standard_B8ms       8                1047552           65536
16                  49152         Standard_B12ms      12               1047552           98304
32                  65536         Standard_B16ms      16               1047552           131072
32                  81920         Standard_B20ms      20               1047552           163840
4                   4096          Standard_B2als_v2   2                1047552           0
4                   8192          Standard_B2as_v2    2                1047552           0
4                   1024          Standard_B2ats_v2   2                1047552           0
8                   8192          Standard_B4als_v2   4                1047552           0
8                   16384         Standard_B4as_v2    4                1047552           0
16                  16384         Standard_B8als_v2   8                1047552           0
16                  32768         Standard_B8as_v2    8                1047552           0
32                  32768         Standard_B16als_v2  16               1047552           0
32                  65536         Standard_B16as_v2   16               1047552           0
32                  65536         Standard_B32als_v2  32               1047552           0
32                  131072        Standard_B32as_v2   32               1047552           0
1                   768           Basic_A0            1                1047552           20480
2                   1792          Basic_A1            1                1047552           40960
4                   3584          Basic_A2            2                1047552           61440
8                   7168          Basic_A3            4                1047552           122880
16                  14336         Basic_A4            8                1047552           245760
4                   4096          Standard_B2ls_v2    2                1047552           0
4                   8192          Standard_B2s_v2     2                1047552           0
4                   1024          Standard_B2ts_v2    2                1047552           0
8                   8192          Standard_B4ls_v2    4                1047552           0
8                   16384         Standard_B4s_v2     4                1047552           0
16                  16384         Standard_B8ls_v2    8                1047552           0
16                  32768         Standard_B8s_v2     8                1047552           0
32                  32768         Standard_B16ls_v2   16               1047552           0
32                  65536         Standard_B16s_v2    16               1047552           0
32                  65536         Standard_B32ls_v2   32               1047552           0
32                  131072        Standard_B32s_v2    32               1047552           0
4                   4096          Standard_B2pls_v2   2                1047552           0
4                   8192          Standard_B2ps_v2    2                1047552           0
4                   1024          Standard_B2pts_v2   2                1047552           0
8                   8192          Standard_B4pls_v2   4                1047552           0
8                   16384         Standard_B4ps_v2    4                1047552           0
16                  16384         Standard_B8pls_v2   8                1047552           0
16                  32768         Standard_B8ps_v2    8                1047552           0
32                  32768         Standard_B16pls_v2  16               1047552           0
32                  65536         Standard_B16ps_v2   16               1047552           0
```

## snippet

```
az vm list-sizes --location westus -o table --query "[?contains(name, 'B')]"
```
