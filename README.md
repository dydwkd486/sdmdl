[![Build Status](https://travis-ci.com/naturalis/sdmdl.svg?branch=master)](https://travis-ci.com/naturalis/sdmdl)
[![License: MIT](https://img.shields.io/badge/License-MIT-success.svg)](https://opensource.org/licenses/MIT)
[![Coverage Status](https://coveralls.io/repos/github/naturalis/sdmdl/badge.svg?branch=master)](https://coveralls.io/github/naturalis/sdmdl?branch=master)
[![Documentation Status](https://readthedocs.org/projects/sdmdl/badge/?version=latest)](https://sdmdl.readthedocs.io/en/latest/?badge=latest)
[![Updates](https://pyup.io/repos/github/naturalis/sdmdl/shield.svg)](https://pyup.io/repos/github/naturalis/sdmdl/)

# sdmdl

An object-oriented python package for species distribution modelling using deep learning.
The package allows for a more intuitive and easy exploration of biodiversity patterns by 
modelling preferences for a great number of environmental variables.

심층 학습을 이용한 종 분포 모델링용 객체 지향형 파이썬 패키지

이 패키지는 수많은 환경 변수에 대한 선호도를 모델링함으로써 생물 다양성 패턴을 보다 직관적이고 쉽게 탐색할 수 있게 해준다.

Instructions for installing and using the sdmdl package can be found [here](docs/index.rst).
sdmdl 패키지의 설치 및 사용에 대한 지침은 [여기](docs/index.rst)에서 확인할 수 있다.

### Case study

The functionality of this package and the estimates of environmental preferences it
obtains is demonstrated by way of a use case on domesticated crops and their wild progenitors.

이 패키지의 기능성 및 환경적 선호 추정치는 "농작물"과 "wild progenitors"에 대한 사용 사례를 통해 입증된다.

The raw uninterpreted results of this case study can be found [here](https://zenodo.org/record/3460718#.XYuBJEYzaCo). 

이 사례 연구의 미해결 결과는 [여기](https://zenodo.org/record/3460718#.XYuBJEYzaCo)에서 확인할 수 있다.

### Acknowledgments

- [Comparative analysis of abiotic niches in Ungulates](https://github.com/naturalis/trait-geo-diverse-ungulates) by E. Hendrix.
- [Ecological Niche Modelling Using Deep Learning](https://github.com/naturalis/trait-geo-diverse-dl) by M. Rademaker.

### Package layout

- [CONTRIBUTING.md](CONTRIBUTING.md) - hints for how to contribute to this project - 이 프로젝트에 기여하는 방법
- [LICENSE](LICENSE) - the MIT license, which applies to this package
- [README.md](README.md) - the README file, which you are now reading - 지금 읽고 있는 README 파일
- [requirements.txt](requirements.txt) - prerequisites to install this package, used by pip - pip에서 사용하는 이 패키지를 설치하기 위한 필수 구성 요소
- [setup.py](setup.py) - installer script
- [data](data)/ - contains some files that are (currently) required for data preprocessing - **marked for deletion**
- [docs](docs)/ - contains documentation on package installation and usage - 패키지 설치 및 사용에 대한 설명서 포함
- [sdmdl](sdmdl)/ - the library code itself
- [tests](tests)/ - unit tests

## 한국어 추가
2019-10-25 Readme 수정

- 설치과정이 안되는 문제를 docs의 파일을 수정해서 적어 놓기
- 파일 위치를 통해 실제 파일이 실행되게끔하기
- 환경 자료들도 추가적으로 적어서 테스트 한번 돌릴수있게 적어 놓기
