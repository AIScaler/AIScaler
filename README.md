# AIScaler

<div align="center">

#### Free and Open Source AI Image Upscaler
AI Scaler make you enlarge and enhance low-resolution images using advanced AI algorithms.
Enlarge images without losing quality.

</div>

> [!IMPORTANT]
> You'll need a Vulkan compatible GPU to upscale images. Many CPU and iGPUs do not work but no harm in trying.

# 👨‍💻 Installation

### 🐌 Windows Only
(Windows 10 and later)

1. Go to [releases section](https://github.com/aiscaler/aiscaler/releases/latest)
2. Download the `.exe` file.
3. Double click exe file, wait for installation, profit.

# 🛠 Development

## ▶ Running

> [!NOTE]
> If you are not willing to install [git](https://git-scm.com/downloads), you can skip the first line, download [the source zip](https://github.com/aiscaler/aiscaler/archive/refs/heads/main.zip) and extract it to `aiscaler` instead and carry on with the rest of the instructions.

```sh
git clone https://github.com/aiscaler/aiscaler
cd aiscaler

# INSTALL DEPENDENCIES
pip install -r requirements.txt

# RUN PROGRAM
python AIScaler.py
```
## 🏗️ Building

```sh
# INSTALL DEPENDENCIES
install -r requirements.txt

# RUN
pyinstaller aiscaler.spec
```

# Credits

- Real-ESRGAN for their wonderful research work. [Real-ESRGAN: Copyright (c) 2021, Xintao Wang](https://github.com/xinntao/Real-ESRGAN/)

# License

Copyright 2023 zeindevs

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

	http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.