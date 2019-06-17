# zc702_dpu140_trd

This TRD is implement DPU v1.4.0 on Xilinx zc702 board.

## Prerequisites 
- Xilinx Vivado v2018.3
- Xilinx Petalinux v2018.3
- Xilinx DNNDK v3.0
- Xilinx DPU IP v1.4.0


## File tree in this git project

- apps(CNN example applications)
- dpu_ip_v140 (DPU IP source files)
- Hands-On.md (hands on guide)
- petalinux (files for petalinux project)
- vivado (files for vivado project)
- zynq7020_dnndk_v3.0 (bin and runtime of dnndk v3.0 for zynq device)

```
zc702_dpu140_trd$ tree -L 2
.
├── apps
│   └── zc702_yolov3_8g
├── dpu_ip_v140
│   └── dpu
├── Hands-On.md
├── petalinux
│   └── bsp
├── README.md
├── vivado
│   ├── zc702_dpu140_0613.tcl
│   ├── zc702_dpu140_bd_0613.tcl
│   ├── zc702_dpu140_design1.pdf
│   └── zc702_dpu140_design1_wrapper.hdf
└── zynq7020_dnndk_v3.0
    ├── install.sh
    ├── install.sh.orig
    └── pkgs

9 directories, 9 files
```

## Hands-On
See the Hands-On.md for details.

## Authors
- Alex He (alex.he@xilinx.com)


