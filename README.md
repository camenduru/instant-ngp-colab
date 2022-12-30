[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/camenduru/instant-ngp-colab/blob/main/instant_ngp.ipynb)

## Main Repo
https://github.com/NVlabs/instant-ngp


## Viewer for Windows (Built with CUDA Toolkit 12.0)
- Install latest Nvidia Driver
https://www.nvidia.com/download/index.aspx

- Install Microsoft Visual C++ Redistributable  (Visual Studio 2015, 2017, 2019, and 2022)
https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170#visual-studio-2015-2017-2019-and-2022
https://aka.ms/vs/17/release/vc_redist.x64.exe

- Download the Viewer
  - [GTX 1000 series, Titan Xp, Quadro P1000–P6000, and other Pascal cards](https://github.com/camenduru/instant-ngp-colab/releases/download/v1.0/instant-ngp-win-1000.zip)
  - RTX 2000 series, Titan RTX, Quadro RTX 4000–8000, and other Turing cards
  - RTX 3000 & 4000 series, RTX A4000–A6000, and other Ampere & Ada cards

- CMD for view trained model 
  - `.\build\instant-ngp --scene data\nerf\fox --no-train --snapshot data\nerf\fox\20000.msgpack`

