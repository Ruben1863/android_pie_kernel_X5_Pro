# android_pie_kernel_X5_Pro
Pie kernel 3.18 for Doogee X5 Pro. By Ruben1863

This custom kernel (3.18.119) source made to DOOGEE X5 Pro (MT6735).

## Known information:
| Subsystem | Driver name | Availability | Working |
|-----------|-------------|--------------|---------|
| LCM driver | `hct_rm68200_dsi_vdo_hd_cpt` | Yes | Yes |
| Touch panel | `FT5X05 (i2c 1-0038)` | Yes | - |
| GPU | `Mali-T720 MP2` | Yes | Yes |
| Camera #1 | `s5k5e2y_mipi_raw` | Yes | - |
| Camera #2 | `gc2355_mipi_raw` | Yes | - |
| Accelerometer | ` (i2c 2-0015)` | Yes | - |
| ALS/PS | `EPL2182 (i2c 2-0049)` | Yes | - |
| Flash | `Micron R1J96N` | - | Yes |
| Lens | `FM50AF` | Yes | - |
| RAM | `2 GB LPDDR3_1600` | - | Yes |
| Sound | `mtsndcard` | Yes | - |
| Accdet | `mt6580-accdet` | - | Yes |
| Other | `kd_camera_hw (i2c 0-0010)` | Yes | - |

## Build process:
* Clone that repo, by running:
`git clone https://github.com/ruben1863/android_pie_kernel_X5_Pro kernel`
* Start the build:
`cd kernel ; bash Build`
  - Output kernel will be in out/arch/arm/boot/zImage-dtb

## Acknowledgements:
- Me for now :)
