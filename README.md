# LandMap-Segmentation with PyTorch 🔥

[![MIT License](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT)

## Image Object Segmentation of Land Cover Map Using Aerial Data

-   항공 사진 내 픽셀이 건물인지 아닌지 분할

### Develop Environment

-   Ubuntu Server 22.04 LTS
-   Python 3.8.15
-   Anaconda 22.9.0
-   Pytorch 1.13.0

### requirements

```bash
pip install -r requirements.txt
```

<details>
<summary>Directory Structure</summary>
<div>

-   data

    -   데이터가 생성되는 모든 위치에서 데이터를 수집하고 추가 기능 엔지니어링이 발생할 수 있는 상태가 되도록 데이터를 변환하는 `Script`가 있습니다.

-   feature

    -   데이터를 조작하고 모델에서 사용할 수 있는 형식으로 저장하는 `Script`가 있습니다.

-   models

    -   모델을 빌드하고 훈련하는 데 사용되는 `Script`가 있습니다.

-   notebook - `.ipynb` 확장자의 notbook들을 정리해둔 디렉토리 입니다.

</div>
</details>
