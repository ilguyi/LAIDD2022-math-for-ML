# Introduction mathematics for machine learning [Lectures on AI-driven Drug Discovery 2022]

* **이 저장소는 한국제약바이오협회 인공지능신약개발지원센터에서 제공하는
Lectures on AI-driven Drug Discovery(LAIDD) 강의의 일환으로 제작되었습니다.**


이 강의는 machine learning을 위한 기초수학 강의의 실습을 위해 만들어졌습니다.

1. Linear algebra
2. Probability theory

선형대수학과 기초 확률에 대한 강의와 실습을 목표로 합니다.


* Final update: 2022. 8. 29.
* All right reserved @ 이일구 (Il Gu Yi) 2022
* 이 저장소는 Ubuntu, Linux Mint 및 MacOS에서 테스트 되었습니다.
  * Windows는 별도의 테스트를 하지 못하였으나 가상환경 및 패키지설치가 된다면 사용가능할 것으로 생각됩니다.
* Lectures on AI-driven Drug Discovery(LAIDD) 사이트: [https://www.laidd.org](https://www.laidd.org)


## Getting Started

### Prerequisites

* `python` >= 3.8
* [`pytorch`](https://pytorch.org) >= 1.13
* `numpy`, `pandas`, `matplotlib`
* `jupyterlab`


## Installation

### 가상환경 만들기

이 패키지는 [`anaconda`](https://anaconda.org/) 환경에서 실행하는 것을 추천합니다.
먼저 `conda`를 이용하여 가상환경을 만듭니다.
```bash
$ conda create --name laidd22math python=3.8
$ conda activate laidd22math
```

`git clone`을 통해 이 패키지를 다운 받습니다.
그 후 `conda install {package}`를 통해 패키지 설치를 합니다.
```bash
$ git clone https://github.com/ilguyi/LAIDD2022-math-for-ML
$ cd LAIDD2022-math-for-ML
$ conda install numpy pandas matplotlib
$ conda install -c conda-forge jupyterlab
```
pytorch는 홈페이지에서 자신의 환경에 맞게 설치를 합니다.
[설치페이지 바로가기](https://pytorch.org/get-started/locally/)


## Execution
모든 패키지 설치가 끝났으면 `jupyterlab`을 실행합니다.
```bash
$ jupyter lab
```


## Author

* 이일구 (Il Gu Yi)
* e-mail: ilgu.yi.work@gmail.com
